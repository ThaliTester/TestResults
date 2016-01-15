#### Test 56204092c98eeae_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277519146327; DSPS: 9234653; Offset : -4316685033
,D/AndroidRuntime( 7130): 
D/AndroidRuntime( 7130): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7130): CheckJNI is OFF
D/AndroidRuntime( 7130): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1959): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{332c11b3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{332c11b3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7149 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7130): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1870): Display #0 changed.
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{30cf36fe co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{316ffe5f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7149): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7149): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7149): Loading: webviewchromium
I/LibraryLoader( 7149): Time to load native libraries: 11 ms (timestamps 2272-2283)
I/LibraryLoader( 7149): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7149): Binding Chromium to main looper Looper (main, tid 1) {334f862e}
I/LibraryLoader( 7149): Expected native library version number "",actual native library version number ""
I/chromium( 7149): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7149): Initializing chromium process, renderers=0
W/art     ( 7149): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7149): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7149): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7149): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb15224a0, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d428a5:true
I/Adreno-EGL( 7149): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7149): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7149): Build Date: 12/12/14 금
I/Adreno-EGL( 7149): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7149): Remote Branch: 
I/Adreno-EGL( 7149): Local Patches: 
I/Adreno-EGL( 7149): Reconstruct Branch: 
W/chromium( 7149): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7149): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7149): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7149): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7149): CordovaWebView is running on device made by: LGE
W/art     ( 7149): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7149): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7149): Render dirty regions requested: true
I/OpenGLRenderer( 7149): Initialized EGL, version 1.4
D/OpenGLRenderer( 7149): Enabling debug mode 0
D/Atlas   ( 7149): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{777b0f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7149): LgDataFeature() Constructor: none
D/LgDataFeature( 7149): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1471): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26a64d4b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +646ms (total +741ms)
I/Timeline( 7149): Timeline: Activity_idle id: android.os.BinderProxy@2d3fd6de time:282765
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{1a9a4370 u0 com.test.thalitest/.MainActivity t4} time:282766
D/JsMessageQueue( 7149): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7149): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435088128
D/JX-Cordova( 7149): jxcore cordova android initializing
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
W/jxcore-log( 7149): Initializing JXcore engine
W/jxcore-log( 7149): JXcore engine is ready
,W/jxcore-log( 7149): Starting JXcore engine
,W/.test.thalitest( 7149): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7459]" dev="sockfs" ino=7459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7149): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7149): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9965]" dev="sockfs" ino=9965 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7149): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7149): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33586]" dev="sockfs" ino=33586 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7149): Platform android
W/jxcore-log( 7149): 
W/jxcore-log( 7149): Process ARCH arm
W/jxcore-log( 7149): 
,I/jxcore-log( 7149): JXcore Cordova bridge is ready!
I/jxcore-log( 7149): 
W/jxcore-log( 7149): JXcore engine is started
,I/jxcore-log( 7149): Toggling radios to true
I/jxcore-log( 7149): 
,D/BluetoothAdapter( 7149): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7149, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7149, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1037): disconnect pid=7149, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [286,628,412 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7149, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7149): Radios toggled
I/jxcore-log( 7149): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7149): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7149): 
I/jxcore-log( 7149): Perf Test app loaded loaded
I/jxcore-log( 7149): 
I/jxcore-log( 7149): check test folder
I/jxcore-log( 7149): 
I/jxcore-log( 7149): found test : ./testFindPeers.js
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): found test : ./testSendData.js
,I/jxcore-log( 7149): 
,I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): InitialState.processMessage what=4
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2131): Read error: ssl=0xaa76b000: I/O error during system call, Connection timed out
V/NativeCrypto( 2131): SSL shutdown failed: ssl=0xaa76b000: I/O error during system call, Broken pipe
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
I/art     (  351): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 516us total 28.513ms
E/WifiNative: ( 1037): [286,732,927 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
,I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286760
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286761
I/art     (  351): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 20.193ms
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 19.051ms
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/DSQN    ( 1037): stop dsqn bin
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/WifiHS20( 1037): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286796  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286797  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524292
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
,D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286814  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286817  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,W/ResourcesManager( 7229): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7229): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7229): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7229): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7229): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7229): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-117ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/chromium( 7149): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7149): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7149): 
I/chromium( 7149): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7229): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7229): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7229): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7229): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7229): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7229): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7266 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6618:com.android.defcontainer/u0a4 (adj 15): empty #17
I/chromium( 7149): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7149): 
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6618/cgroup.procs: No such file or directory
,I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7266): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7229): LgDataFeature() Constructor: none
D/LgDataFeature( 7229): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7290 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6715:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6715/cgroup.procs: No such file or directory
,W/ResourcesManager( 7290): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7290): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7290): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7290): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7290): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7290): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7290): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7290): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7290): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7290): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7266): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/QRemote ( 7290): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7266): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7266): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7290): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7290): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7290): LgDataFeature() Constructor: none
,D/LgDataFeature( 7290): LgDataFeature() Constructor Done, null
V/SoundPool( 7290): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7290): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7290): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7290): doLoad: loading sample sampleID=1
,I/QRemote ( 7290): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7290): Start decode
V/MediaPlayer[Native]( 7290): decode(31, 10857164, 17813)
D/QRemote ( 7290): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb54745c0, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/UEI.SmartControl( 6879): QS Service created
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
E/QRemote ( 7290): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7290): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7290): Create singleton instance
I/UEI.SmartControl( 6879): Service initServices...
D/UEI.SmartControl( 6879): QS start get config
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
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
,V/AwesomePlayer(  316): getUseOffload() = 0 
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
,V/AudioCache(  316): notify(0xb54745c0, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb54745c0, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
,V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1003790 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb54745c0, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab700000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab701000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab702000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab703000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab704000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab705000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab706000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab707000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab708000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab709000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70a000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70b000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70c000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70d000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70e000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab70f000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab710000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab711000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab712000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab713000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab714000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab715000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab716000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab717000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab718000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab719000, 0xb57e9000, 4096),
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab71a000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab71b000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab71c000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
,V/AudioCache(  316): memcpy(0xab71d000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab71e000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
,V/AudioCache(  316): memcpy(0xab71f000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab720000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab721000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab722000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab723000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab724000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab725000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab726000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab727000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab728000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab729000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72a000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72b000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72c000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72d000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72e000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab72f000, 0xb57e9000, 4096)
V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab730000, 0xb57e9000, 4096)
,V/AudioCache(  316): write(0xb57e9000, 4096)
V/AudioCache(  316): memcpy(0xab731000, 0xb57e9000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb57e9000, 280)
V/AudioCache(  316): memcpy(0xab732000, 0xb57e9000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb54745c0, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb54745c0, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/AudioCache(  316): wait - success
,V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  316): Pause Playback at 1068125
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb54745c0, 8, 0, 0)
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
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1003790 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 1
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
V/SoundPool( 7290): close(31)
V/SoundPool( 7290): pointer = 0x9ffc9000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7290): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:683
I/UEI.SmartControl( 6879): Supports setup maps: true
,D/UEI.SmartControl( 6879): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6879): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6879): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6879): ### init IR Blaster...
D/serial_port( 6879): Configuring serial port
E/UEI.SmartControl( 6879): UEIBLaster setting for 616
I/UEI.SmartControl( 6879): Setting serial record hearder size = 2
I/UEI.SmartControl( 6879): configuring settings for MAXQ616
I/UEI.SmartControl( 6879): Get version...
D/UEI.SmartControl( 6879): serial port data available: 21
,D/UEI.SmartControl( 6879): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6879): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6879): QS saving settings...
D/UEI.SmartControl( 6879): IR Blaster version: 25672567
,D/UEI.SmartControl( 6879): serial port data available: 4
,I/UEI.SmartControl( 6879): Device manager: loading config....
D/UEI.SmartControl( 6879): ----------- loading internal config...
W/ContextImpl( 6879): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6879): Services init done
D/UEI.SmartControl( 6879): QS Service init finished
D/UEI.SmartControl( 6879): QS Service version name: 2.1.91
D/UEI.SmartControl( 6879): QS Service version code: 201091
D/UEI.SmartControl( 6879): Service requested: Control
E/UEI.SmartControl( 6879): Loading SETTINGS...
,D/UEI.SmartControl( 6879): Request IControl service: devices are loaded...
I/QRemote ( 7290): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6879): Internal service binding...
I/UEI.SmartControl( 6879): ------ IControl API: 11
D/UEI.SmartControl( 6879): File observer start...
E/UEI.SmartControl( 6879): IR Port is disabled: false
D/UEI.SmartControl( 6879): Starting file observer...
I/UEI.SmartControl( 6879): Registering callback...
,I/UEI.SmartControl( 6879): ------ IControl API: 19
I/UEI.SmartControl( 6879): Registering Services Ready callback...
D/UEI.SmartControl( 6879): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6879): Notify AllClients services are ready: 0
,I/QRemote ( 7290): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7290): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7290): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7290): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/UEI.SmartControl( 6879): -----service ready thread exits
D/QRemote ( 7290): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6879): ------ IControl API: 8
D/QRemote ( 7290): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7290): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7290): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7290): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7290): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7290): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7290): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7290): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7290): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7290): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452883697604]
D/QRemote ( 7290): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6740:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7290): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6740/cgroup.procs: No such file or directory
V/QRemote ( 7290): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7290): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2682): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=288947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=288967  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2682): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 2682): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2682): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289059  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289060  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
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
,E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289068
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289068
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289069
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289070
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289070
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289081  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289102  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289105  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289106  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289106
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289107
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7229): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7229): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7229): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7229): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7229): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7229): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7229): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  312): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289158  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289159  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289159  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289167  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289168  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289168  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23aedae8 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23aedae8 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  312): Setting iface cfg
D/CommandListener(  312): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
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
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  312): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
,D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7362): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7362): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7362): DSQN ssw
,D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7290): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7290): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7290): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7290): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
I/PCSuite ( 7266): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7266): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7229): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7229): MCCMNC not supported: null
,D/QRemote ( 7290): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7290): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7290): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7290): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7290): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  312): argv[0]=dsqncommand
D/LGDataListener(  312): argv[1]=wlan0
D/LGDataListener(  312): argv[2]=1
D/LGDataListener(  312): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 18:48:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452883698621], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452883698599]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
W/dhcpcd  ( 7368): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7368): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/dhcpcd  ( 7368): version 5.5.6 starting
,E/dhcpcd  ( 7368): get_duid: m
D/dhcpcd  ( 7368): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7368): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7368): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7368): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7368): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7368): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7368): wlan0: sending REQUEST (xid 0xe7fc35b9), next in 3.37 seconds
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=290661309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{19d8cbc4 type 2 when 289798 com.google.android.gms} when 289798
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/[Concierge]Service( 2584): onStartCommand(). Type : 9
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5909): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5909): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7397 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7397): onCreate
,W/AppUp4:DB( 7397):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7397):  setFingerPrint start
I/AppUp4:DB( 7397):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7397):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7397):  SDK version = 21
I/AppUp4:DB( 7397):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7397): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7397): onReceive
,D/LgDataFeature( 7397): LgDataFeature() Constructor: none
,D/LgDataFeature( 7397): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7397): Context : android.app.ReceiverRestrictedContext@3b4dcb5c
,D/AppUp4:CustFacade( 7397): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7397): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7397): begin check event
I/AppUp4:CustModeStarterReceiver( 7397): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7397): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7397): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7397): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7397): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6759:com.android.contacts/u0a19 (adj 15): empty #17
,D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6759/cgroup.procs: No such file or directory
,D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4342): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4342): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3412): DownloadService onCreate
I/DownloadManager( 3412): in removeSpuriousFiles
,V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@34d1b4f9 on behalf of 3412
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3412): in trimDatabase
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@14041c3e on behalf of 3412
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3412): DownloadService onStartCommand
E/LGDMClient( 4342): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4342): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4342): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@1cefa7b5 on behalf of 3412
V/DownloadManager( 3412): processing inserted download 1
V/DownloadManager( 3412): processing inserted download 4
,V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
V/DownloadManager( 3412): processing inserted download 10
V/DownloadManager( 3412): processing inserted download 16
V/DownloadManager( 3412): processing inserted download 17
V/DownloadManager( 3412): processing inserted download 18
V/DownloadManager( 3412): processing inserted download 21
D/eas_req ( 6783): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3412): DownloadService onDestroy
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7431 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6783): JNI_OnLoad()
I/HubEmail( 6783): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6783): registerNatives()
I/HubEmail( 6783): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6783): registerNativeMethods()
I/HubEmail( 6783): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6783): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 7149): Connected to the server!
I/jxcore-log( 7149): 
,I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
I/chromium( 7149): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7455 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com succeed
,I/dhcpcd  ( 7368): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7368): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7368): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7368): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7368): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7368): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7368): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7368): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7368): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,V/FormManager( 7431): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7431): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7485 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6807:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6807/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6828:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7517 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6852:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6828/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6852/cgroup.procs: No such file or directory
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1a2e4bf type 2 when 290947 android} when 290947
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
,I/art     ( 7517): Almond Protected OAT
,D/WeatherApplication( 7517): removeAccount
,D/WeatherApplication( 7517): Account.length = 0
,E/WeatherApplication( 7517): OPERATOR:OPEN
D/WeatherAncestor( 7517): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:20
D/Weather.Utils( 7517): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7517): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7517): 2 : This is isUpdating : false
D/WeatherAncestor( 7517): connectivity changed - connection : true
,D/WeatherService( 7517): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7517): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7517): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7517): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7517): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7517): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:20
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7538 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6931:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6931/cgroup.procs: No such file or directory
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7538): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7149): BLE supported!!
I/jxcore-log( 7149): 
I/WebViewFactory( 7538): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7538): Loading: webviewchromium
I/LibraryLoader( 7538): Time to load native libraries: 4 ms (timestamps 1701-1705)
I/LibraryLoader( 7538): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7538): Binding Chromium to main looper Looper (main, tid 1) {ffb98b7}
I/LibraryLoader( 7538): Expected native library version number "",actual native library version number ""
I/chromium( 7538): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7538): Initializing chromium process, renderers=0
W/art     ( 7538): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7538): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7538): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7538): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
V/AudioPolicyService(  316): registerClient() client 0xb1522300, uid 10093
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/AudioManagerAndroid( 7538): Requires BLUETOOTH permission
,I/Adreno-EGL( 7538): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7538): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7538): Build Date: 12/12/14 금
I/Adreno-EGL( 7538): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7538): Remote Branch: 
I/Adreno-EGL( 7538): Local Patches: 
I/Adreno-EGL( 7538): Reconstruct Branch: 
,I/NSApplication( 7538): Starting up...
,I/ActivityManager( 1037): Killing 6959:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6959/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7397): onReceive
D/AppUp4:CustFacade( 7397): Context : android.app.ReceiverRestrictedContext@3b4dcb5c
D/AppUp4:CustFacade( 7397): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7397): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7397): begin check event
I/AppUp4:CustModeStarterReceiver( 7397): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4342): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4342): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  312): res_queryN name = mtalk.google.com succeed
V/DownloadManager( 3412): DownloadService onCreate
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4342): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4342): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4342): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3412): in removeSpuriousFiles
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@3effa6d8 on behalf of 3412
V/DownloadManager( 3412): DownloadService onStartCommand
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@39c57516 on behalf of 3412
,I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3412): in trimDatabase
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@27c3be97 on behalf of 3412
V/DownloadManager( 3412): processing inserted download 1
V/DownloadManager( 3412): processing inserted download 4
,V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
V/DownloadManager( 3412): processing inserted download 10
V/DownloadManager( 3412): processing inserted download 16
V/DownloadManager( 3412): processing inserted download 17
V/DownloadManager( 3412): processing inserted download 18
,V/DownloadManager( 3412): processing inserted download 21
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3412): DownloadService onDestroy
W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7517): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:21
,D/Weather.Utils( 7517): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7517): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7517): 2 : This is isUpdating : false
D/WeatherAncestor( 7517): connectivity changed - connection : true
D/WeatherService( 7517): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b51d73a
D/ForecastDataCache( 7517): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7517): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7517): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7517): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7517): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:21
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,W/Kids    ( 2389): [AccountUtils] Account not ready
W/Kids    ( 2389): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2389): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2389): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7431): There are no updated forms. The schedule will be deleted.
V/FormManager( 7431): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2389): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=290661309 [*alarm*], flags=0x0
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 86729(4MB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.149ms total 82.895ms
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GCM     ( 2131): Connected
I/NetworkMonitor( 5909): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GCM     ( 2131): Message class com.google.f.a.a.p
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7397): [onReceive] request level :IDLE....
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppUp4:CustModeStarterReceiver( 7397): onReceive
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AppUp4:CustFacade( 7397): Context : android.app.ReceiverRestrictedContext@3b4dcb5c
D/AppUp4:CustFacade( 7397): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7397): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7397): begin check event
I/AppUp4:CustModeStarterReceiver( 7397): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/BooksSync( 7045): Starting books sync
D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4342): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4342): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3412): DownloadService onCreate
I/LGDMClient( 4342): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3412): in removeSpuriousFiles
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@2d5a186d on behalf of 3412
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3412): in trimDatabase
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@141bcca2 on behalf of 3412
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2389): [AccountUtils] Account not ready
W/Kids    ( 2389): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2389): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2389): 	at java.lang.Thread.run(Thread.java:818)
D/BooksSync( 7045): started syncMyEbooks
W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3412): DownloadService onStartCommand
W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@340cce69 on behalf of 3412
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4342): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3412): processing inserted download 1
W/ContextImpl( 4342): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3412): processing inserted download 4
V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
E/LGDMClient( 4342): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
V/DownloadManager( 3412): processing inserted download 10
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
V/DownloadManager( 3412): processing inserted download 16
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
V/DownloadManager( 3412): processing inserted download 17
V/DownloadManager( 3412): processing inserted download 18
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LGDMClient( 4342): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4342): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3412): processing inserted download 21
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = true
D/PhoneState( 3360): setPdpRejectCasuse : false
V/DownloadManager( 3412): DownloadService onDestroy
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/WeatherAncestor( 7517): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:21
D/Weather.Utils( 7517): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7517): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7517): 2 : This is isUpdating : false
D/WeatherAncestor( 7517): connectivity changed - connection : true
D/WeatherService( 7517): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b51d73a
D/ForecastDataCache( 7517): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7517): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7517): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7517): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7517): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:48:21
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7431): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7431): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
D/ChimeraCfgMgr( 2389): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/LgeQuickCoverNLService( 1418): onNotificationPosted
E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2389): [AccountUtils] Account not ready
W/Kids    ( 2389): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2389): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2389): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2389): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2389): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2389): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
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
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7045): Error response from books API: {
W/ApiaryClient( 7045):  "error": {
W/ApiaryClient( 7045):   "errors": [
W/ApiaryClient( 7045):    {
W/ApiaryClient( 7045):     "domain": "global",
W/ApiaryClient( 7045):     "reason": "required",
W/ApiaryClient( 7045):     "message": "Login Required",
W/ApiaryClient( 7045):     "locationType": "header",
W/ApiaryClient( 7045):     "location": "Authorization"
W/ApiaryClient( 7045):    }
W/ApiaryClient( 7045):   ],
W/ApiaryClient( 7045):   "code": 401,
W/ApiaryClient( 7045):   "message": "Login Required"
W/ApiaryClient( 7045):  }
W/ApiaryClient( 7045): }
,W/ApiaryClient( 7045): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7599279360623541926&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
D/UEI.SmartControl( 6879): Internal timer expired: 3
D/UEI.SmartControl( 6879): unbind internal service
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = www.google.com succeed
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
D/serial_port( 6879): close(fd = 24)
I/UEI.SmartControl( 6879): Serial port is closed.
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7045): Error response from books API: {
W/ApiaryClient( 7045):  "error": {
W/ApiaryClient( 7045):   "errors": [
W/ApiaryClient( 7045):    {
W/ApiaryClient( 7045):     "domain": "global",
W/ApiaryClient( 7045):     "reason": "required",
W/ApiaryClient( 7045):     "message": "Login Required",
W/ApiaryClient( 7045):     "locationType": "header",
W/ApiaryClient( 7045):     "location": "Authorization"
W/ApiaryClient( 7045):    }
W/ApiaryClient( 7045):   ],
W/ApiaryClient( 7045):   "code": 401,
W/ApiaryClient( 7045):   "message": "Login Required"
W/ApiaryClient( 7045):  }
W/ApiaryClient( 7045): }
,W/ApiaryClient( 7045): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7599279360623541926&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7045): Error response from books API: {
W/ApiaryClient( 7045):  "error": {
W/ApiaryClient( 7045):   "errors": [
W/ApiaryClient( 7045):    {
W/ApiaryClient( 7045):     "domain": "global",
W/ApiaryClient( 7045):     "reason": "required",
W/ApiaryClient( 7045):     "message": "Login Required",
W/ApiaryClient( 7045):     "locationType": "header",
W/ApiaryClient( 7045):     "location": "Authorization"
W/ApiaryClient( 7045):    }
W/ApiaryClient( 7045):   ],
W/ApiaryClient( 7045):   "code": 401,
W/ApiaryClient( 7045):   "message": "Login Required"
W/ApiaryClient( 7045):  }
W/ApiaryClient( 7045): }
,W/ApiaryClient( 7045): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7599279360623541926&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
E/BooksSync( 7045): Soft error: 
E/BooksSync( 7045): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7599279360623541926&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7045): Headers:
E/BooksSync( 7045): accept-encoding: [gzip]
E/BooksSync( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7045): gdata-version: 2
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7045): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7045): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7045): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7045): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7045): {
E/BooksSync( 7045):  "error": {
E/BooksSync( 7045):   "errors": [
E/BooksSync( 7045):    {
E/BooksSync( 7045):     "domain": "global",
E/BooksSync( 7045):     "reason": "required",
E/BooksSync( 7045):     "message": "Login Required",
E/BooksSync( 7045):     "locationType": "header",
E/BooksSync( 7045):     "location": "Authorization"
E/BooksSync( 7045):    }
E/BooksSync( 7045):   ],
E/BooksSync( 7045):   "code": 401,
E/BooksSync( 7045):   "message": "Login Required"
E/BooksSync( 7045):  }
E/BooksSync( 7045): }
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7045): 	... 8 more
,E/BooksSync( 7045): Sync error
E/BooksSync( 7045): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7599279360623541926&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7045): Headers:
E/BooksSync( 7045): accept-encoding: [gzip]
E/BooksSync( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7045): gdata-version: 2
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7045): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7045): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7045): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7045): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7045): {
E/BooksSync( 7045):  "error": {
E/BooksSync( 7045):   "errors": [
E/BooksSync( 7045):    {
E/BooksSync( 7045):     "domain": "global",
E/BooksSync( 7045):     "reason": "required",
E/BooksSync( 7045):     "message": "Login Required",
E/BooksSync( 7045):     "locationType": "header",
E/BooksSync( 7045):     "location": "Authorization"
E/BooksSync( 7045):    }
E/BooksSync( 7045):   ],
E/BooksSync( 7045):   "code": 401,
E/BooksSync( 7045):   "message": "Login Required"
E/BooksSync( 7045):  }
E/BooksSync( 7045): }
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7045): 	... 8 more
I/BooksSync( 7045): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 290947, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GAV4    ( 7538): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297520175047; DSPS: 9890047; Offset : -4316693963
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317522355299; DSPS: 10545479; Offset : -4316710847
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3a775e5 type 2 when 322322 android} when 322322
,V/QRemote ( 7290): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7290): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:683
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337524299822; DSPS: 11200902; Offset : -4316688853
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=290661309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2584): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=290661309 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357525958826; DSPS: 11856317; Offset : -4316708238
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6275): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6275): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6275): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6275): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6275): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6275): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377527854807; DSPS: 12511739; Offset : -4316704607
,I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397529892716; DSPS: 13167166; Offset : -4316711219
,I/jxcore-log( 7149): --- start :testFindPeers.js---
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): testFindPeers created [object Object]
I/jxcore-log( 7149): 
I/jxcore-log( 7149): serverPort is 8876
I/jxcore-log( 7149): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT8254
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7149): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7149): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3811): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): start: OK
I/io.jxcore.node.ConnectionHelper( 7149): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT8254
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7149): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bb9e9772 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bb9e9772 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505438323534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505438323534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7149): start: OK
I/jxcore-log( 7149): StartBroadcasting started ok
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7149): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7149): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1959): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] is available
I/jxcore-log( 7149): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT3714","peerAvailable":true}]
I/jxcore-log( 7149): 
I/jxcore-log( 7149): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7149): 
I/jxcore-log( 7149): weAreDoneNow
I/jxcore-log( 7149): 
I/jxcore-log( 7149): done, now sending data to server
I/jxcore-log( 7149): 
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-33ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-33ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-33ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-40ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-40ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-40ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-40ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-40ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-40ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-46ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-46ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-46ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-53ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-53ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-53ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-53ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-53ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-53ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-61ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-61ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-61ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-62ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-62ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-62ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-59ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-59ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-59ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-41ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-41ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:5,0:76:28
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] is available
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417532733907; DSPS: 13822619; Offset : -4316708137
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
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
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000101000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] is available
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121],, add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1959): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=55 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000102000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] is available
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01],
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=64 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437534924055; DSPS: 14478051; Offset : -4316715281
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=73 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=75 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=77 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=80 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=83 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=87 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 3 68000103000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] is available
I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=89 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457537120975; DSPS: 15133482; Offset : -4316685083
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=91 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=93 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=94 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=100 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=102 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=29 target=com.android.internal.util.StateMachine$Sm,Handler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688,
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=103 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000104000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManag,er( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
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
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: A,ndroid_8ae2 52:55:27:f0:fd:0b
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477539249769; DSPS: 15788912; Offset : -4316692389
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=110 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=111 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=112 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=114 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
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
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001010a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=118 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 69000105000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=121 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001060a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=122 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001040a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=123 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 4 120001040a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=124 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=125 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=39 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=39 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=127 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=128 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=129 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=130 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001060a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497541646689; DSPS: 16444351; Offset : -4316706541
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=131 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001070a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=132 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=135 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED ,
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=139 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=140 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=141 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=142 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=144 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
,I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=146 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=147 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=150 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001070a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001070a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001070a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517566268244; DSPS: 17100517; Offset : -4316682153
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=153 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=154 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=155 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=156 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=157 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=160 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=161 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=162 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
,D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=163 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000107000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=164 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=165 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: Android_8ae2
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=167 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=168 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-16ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-16ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-16ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-26ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-26ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-26ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-28ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 9,2:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-26ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-26ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000108000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000108000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=170 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 63000108000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771],
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
,I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] is available
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=171 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027],
D/LGWifiP2pService( 1037): InactiveState{ when=-26ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-26ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=172 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01
I/jxcore-log( 7149): teardown
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): testFindPeers stopped
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1959): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=173 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7149): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setState: NOT_STARTED
I/jxcore-log( 7149): StopBroadcasting went ok
I/jxcore-log( 7149): 
I/jxcore-log( 7149): --- start :testSendData.js---
I/jxcore-log( 7149): 
I/jxcore-log( 7149): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): daya100000
I/jxcore-log( 7149): 
I/jxcore-log( 7149): check server
I/jxcore-log( 7149): 
I/jxcore-log( 7149): serverPort is 33380
I/jxcore-log( 7149): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT8254
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7149): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7149): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): start: OK
I/io.jxcore.node.ConnectionHelper( 7149): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT8254
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7149): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bb9e9772 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bb9e9772 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505438323534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505438323534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7149): start: OK
I/jxcore-log( 7149): StartBroadcasting started ok
I/jxcore-log( 7149): 
I/jxcore-log( 7149): null
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:18.563Z SendDataTCPServer.js: TCP/IP server is bound to port: 33380
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7149): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7149): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1959): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=174 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7149): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/chromium( 7149): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7149): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=175 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=176 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=177 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1959): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=179 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=180 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 68000109000a436f72646f7661703270c00c000c01527b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a2273616d73756e672d534d2d4e393130435f505438393939222c227261223a2245303a44423a31303a31343a45323a4330227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=290661309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3864c34b type 2 when 536553 android} when 536553
D/[Concierge]Service( 2584): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=290661309 [*alarm*], flags=0x0
,I/BooksSync( 7045): Starting books sync
,D/BooksSync( 7045): started syncMyEbooks
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537568524538; DSPS: 17755951; Offset : -4316684212
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ApiaryClient( 7045): errCount = 1: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: java.io.EOFException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6878452804498522279&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001050a436f72646f7661703270c00c000c01]
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=182 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 56889(3MB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 2.103ms total 172.019ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=183 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=184 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
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
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=185 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001080a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=186 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001080a436f72646f7661703270c00c000c01
W/ApiaryClient( 7045): Error response from books API: {
W/ApiaryClient( 7045):  "error": {
W/ApiaryClient( 7045):   "errors": [
W/ApiaryClient( 7045):    {
W/ApiaryClient( 7045):     "domain": "global",
W/ApiaryClient( 7045):     "reason": "required",
W/ApiaryClient( 7045):     "message": "Login Required",
W/ApiaryClient( 7045):     "locationType": "header",
W/ApiaryClient( 7045):     "location": "Authorization"
W/ApiaryClient( 7045):    }
W/ApiaryClient( 7045):   ],
W/ApiaryClient( 7045):   "code": 401,
W/ApiaryClient( 7045):   "message": "Login Required"
W/ApiaryClient( 7045):  }
W/ApiaryClient( 7045): }
,W/ApiaryClient( 7045): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6878452804498522279&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=187 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=188 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2131): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2131): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2131): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2131): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2131): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7045): Authentication error
E/BooksAccountManager( 7045): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7045): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7045): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7045): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7045): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{12345884 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7045): Error response from books API: {
W/ApiaryClient( 7045):  "error": {
W/ApiaryClient( 7045):   "errors": [
W/ApiaryClient( 7045):    {
W/ApiaryClient( 7045):     "domain": "global",
W/ApiaryClient( 7045):     "reason": "required",
W/ApiaryClient( 7045):     "message": "Login Required",
W/ApiaryClient( 7045):     "locationType": "header",
W/ApiaryClient( 7045):     "location": "Authorization"
W/ApiaryClient( 7045):    }
W/ApiaryClient( 7045):   ],
W/ApiaryClient( 7045):   "code": 401,
W/ApiaryClient( 7045):   "message": "Login Required"
W/ApiaryClient( 7045):  }
W/ApiaryClient( 7045): }
,W/ApiaryClient( 7045): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6878452804498522279&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7045): Headers:
W/ApiaryClient( 7045): accept-encoding: [gzip]
W/ApiaryClient( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7045): gdata-version: 2
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=189 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1959): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=190 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=191 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010a000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] is available
I/jxcore-log( 7149): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT3213","peerAvailable":true}]
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): Found peer : samsung-SM-G900F_PT3213, Available: true
I/jxcore-log( 7149): 
I/jxcore-log( 7149): startWithNextDevice
I/jxcore-log( 7149): 
I/jxcore-log( 7149): device[1]: B0:C5:59:3F:75:69
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:34.741Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:34.741Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:34.741Z SendDataConnector.js: do connect now
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7149): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 7149): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 841)
,W/LGMDMUISystemServiceAdapter( 7149): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7149): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3811): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3811): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: b0c5593f7569  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3811): [BTUI] connectSocket FD=85 mFd=84
E/BooksSync( 7045): Soft error: 
E/BooksSync( 7045): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6878452804498522279&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7045): Headers:
E/BooksSync( 7045): accept-encoding: [gzip]
E/BooksSync( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7045): gdata-version: 2
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7045): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7045): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7045): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7045): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7045): {
E/BooksSync( 7045):  "error": {
E/BooksSync( 7045):   "errors": [
E/BooksSync( 7045):    {
E/BooksSync( 7045):     "domain": "global",
E/BooksSync( 7045):     "reason": "required",
E/BooksSync( 7045):     "message": "Login Required",
E/BooksSync( 7045):     "locationType": "header",
E/BooksSync( 7045):     "location": "Authorization"
E/BooksSync( 7045):    }
E/BooksSync( 7045):   ],
E/BooksSync( 7045):   "code": 401,
E/BooksSync( 7045):   "message": "Login Required"
E/BooksSync( 7045):  }
E/BooksSync( 7045): }
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7045): 	... 8 more
E/BooksSync( 7045): Sync error
E/BooksSync( 7045): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7045): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6878452804498522279&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7045): Headers:
E/BooksSync( 7045): accept-encoding: [gzip]
E/BooksSync( 7045): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7045): gdata-version: 2
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7045): 	at com.google.android.apps.boo,ks.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7045): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7045): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7045): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7045): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7045): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7045): {
E/BooksSync( 7045):  "error": {
E/BooksSync( 7045):   "errors": [
E/BooksSync( 7045):    {
E/BooksSync( 7045):     "domain": "global",
E/BooksSync( 7045):     "reason": "required",
E/BooksSync( 7045):     "message": "Login Required",
E/BooksSync( 7045):     "locationType": "header",
E/BooksSync( 7045):     "location": "Authorization"
E/BooksSync( 7045):    }
E/BooksSync( 7045):   ],
E/BooksSync( 7045):   "code": 401,
E/BooksSync( 7045):   "message": "Login Required"
E/BooksSync( 7045):  }
E/BooksSync( 7045): }
E/BooksSync( 7045): 
E/BooksSync( 7045): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7045): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7045): 	... 8 more
I/BooksSync( 7045): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 536553, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 3811): btm_acl_created hci_handle=2 link_role=1  transport=1
,W/bt-btm  ( 3811): btm_acl_created hci_handle=2 link_role=0  transport=1
,W/bt-l2cap( 3811): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3811): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3811): btm_read_remote_version_complete: BDA: b0-c5-59-3f-75-69
,W/bt-btm  ( 3811): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,W/bt-btm  ( 3811): btm_process_remote_ext_features_page 0: BDA: b0-c5-59-3f-75-69
,W/bt-btm  ( 3811): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3811): btm_process_remote_ext_features_page 1: BDA: b0-c5-59-3f-75-69
W/bt-btif ( 3811): info:x10
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3811): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3811): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3811): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e58ab1e:true
,D/LGBluetoothFeatureConfig( 7229): isPrivacyLogsEnabled : true
D/LGBluetoothPowerSaveListener( 7229): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3811): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3811): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3811): process_service_search_attr_rsp
W/bt-l2cap( 3811): L2CA_DisconnectReq()  CID: 0x0040
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3811): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: b0c5593f7569  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3811): L2CAP - st: CLOSED evt: 21
I/BluetoothBondStateMachine( 3811): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3811): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3811): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3811): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3811): Entering PendingCommandState State
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7761 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@322651cc:true
,E/ActivityThread( 7761): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7761): No ProfileInfo entries
I/LG Account v2.2( 7761): isEnabled: false
I/Feature ( 7761): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7761): [Lifetracker]Country: EU
I/Feature ( 7761): [Lifetracker]Operator: OPEN
I/Feature ( 7761): [Lifetracker]Ranking support: false
I/Feature ( 7761): [Lifetracker]Comfort support: false
I/Feature ( 7761): [Lifetracker]Accessory: true
I/Feature ( 7761): [Lifetracker]Health device: true
I/Feature ( 7761): [Lifetracker]Extra Pedometer: false
I/Feature ( 7761): [Lifetracker]Blood glucose device: false
I/Feature ( 7761): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 6978:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3811): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothRemoteDevices( 3811): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3811): Failed to remove device: B0:C5:59:3F:75:69
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6978/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 3811): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3811): StableState(): Entering Off State
,W/bt-btm  ( 3811): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3811): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=192 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 120001090a436f72646f7661703270c00c000c01]
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3811): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3811): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3811): new conn_srvc id:26, app_id:1
W/bt-btif ( 3811): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3811): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3811): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 841)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): onBytesWritten: 77 bytes successfully written (thread ID: 842)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Outgoing connection initialized (*handshake* thread ID: 842)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Exiting thread (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Entering thread (ID: 842)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): onBytesRead: Read 82 bytes successfully (thread ID: 842)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Exiting thread (ID: 842)
,W/bt-l2cap( 3811): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3811): L2CAP - st: TERM_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3811): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: b0c5593f7569  p_ertm_info:0x00000000
W/bt-l2cap( 3811): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 24
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3811): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0042,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3811): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0042,PSM: 1,peer MTU present: 0,peer MTU: 672
I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/io.jxcore.node.ConnectionHelper( 7149): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7149): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7149): Entering thread (ID: 843)
D/io.jxcore.node.OutgoingSocketThread( 7149): Server socket local port: 47162
I/io.jxcore.node.OutgoingSocketThread( 7149): Now accepting connections...
W/bt-l2cap( 3811): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3811): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3811): new conn_srvc id:26, app_id:255
W/bt-btif ( 3811): new conn_srvc id:26, app_id:255 count:2
W/bt-btif ( 3811): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3811): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3811): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Incoming connection initialized (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Entering thread (ID: 844)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): onBytesRead: Read 82 bytes successfully (thread ID: 844)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): onBytesWritten: 77 bytes successfully written (thread ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): removeThreadFromList: Removing thread with ID 844
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Handshake thread disposed (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Exiting thread (ID: 844)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/io.jxcore.node.ConnectionHelper( 7149): hasConnection: We have an outgoing connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 7149): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], created successfully
D/io.jxcore.node.ConnectionHelper( 7149): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 7149): Entering thread (ID: 845)
I/jxcore-log( 7149): 2016-01-15T18:52:37.943Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7149): 
,I/io.jxcore.node.IncomingSocketThread( 7149): Local host address: localhost/127.0.0.1, port: 33380
,D/io.jxcore.node.IncomingSocketThread( 7149): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7149): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7149): Exiting thread (ID: 845)
D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 847, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 846, name: Sender)
I/io.jxcore.node.ConnectionHelper( 7149): onListeningForIncomingConnections: Outgoing connection is using port 47162 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 7149): 2016-01-15T18:52:38.129Z SendDataConnector.js: CLIENT connected to 47162, error: null
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:38.130Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7149): 
,I/io.jxcore.node.IncomingSocketThread( 7149): Incoming data from address: /127.0.0.1, port: 47162
D/io.jxcore.node.IncomingSocketThread( 7149): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7149): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7149): Exiting thread (ID: 843)
I/jxcore-log( 7149): 2016-01-15T18:52:38.164Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7149): 
,D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 849, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 848, name: Sender)
I/jxcore-log( 7149): 2016-01-15T18:52:38.839Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:38.841Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:38.857Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:38.993Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:38.999Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.005Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:39.013Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.150Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.187Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.304Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.609Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:39.845Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.147Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.330Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.479Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.533Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.559Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.600Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.637Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.638Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.664Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.750Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.793Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.817Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.822Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.823Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7149): 
I/jxcore-log( 7149): oneRoundDownNow
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.824Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.824Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7149): 
D/io.jxcore.node.ConnectionHelper( 7149): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.IncomingSocketThread( 7149): close
D/io.jxcore.node.IncomingSocketThread( 7149): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 849
D/io.jxcore.node.IncomingSocketThread( 7149): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 848
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 848, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7149): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7149): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 849, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7149): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7149): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 848, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 849, name: Receiver)
I/jxcore-log( 7149): 2016-01-15T18:52:40.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 7149): 
I/jxcore-log( 7149): ---- round done--------
I/jxcore-log( 7149): 
I/jxcore-log( 7149): startWithNextDevice
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.849Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.858Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:40.898Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.913Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:40.984Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 7149): 
,W/bt-rfcomm( 3811): rfc_port_closed
,W/bt-btif ( 3811): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
I/jxcore-log( 7149): 2016-01-15T18:52:41.064Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:41.111Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:41.147Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:41.683Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:41.695Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:41.706Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:41.718Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:41.736Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7149): 
,W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3811): invalid rfc slot id: 7
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 847, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 7149): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 845
D/io.jxcore.node.IncomingSocketThread( 7149): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 847
D/io.jxcore.node.IncomingSocketThread( 7149): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 846
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 846, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7149): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7149): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7149): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 846, name: Sender)
,W/bt-l2cap( 3811): L2CA_DisconnectReq()  CID: 0x0041
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 847, name: Receiver)
W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_DISC_RSP evt: 17
,I/jxcore-log( 7149): 2016-01-15T18:52:41.859Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7149): 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/btif_config_util( 3811): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=193 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=194 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=195 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 120001090a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=196 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/bt-btm  ( 3811): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -1
I/BluetoothMapService( 3811): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3811): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3811): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3811): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3811): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3811): state: -2147483648
D/LGBluetoothPowerSaveListener( 7229): [BTUI] ACL disconnected => AclLinkCount = 0
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@de05b2a:true
,I/BTConnectionReceiver( 4625): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4625): Bluetooth Device Name: Thali Test (Galaxy S5)
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=197 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=198 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557569638748; DSPS: 18411348; Offset : -4316699334
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=199 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=200 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=201 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010b000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=202 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010b000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7149): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] is available
I/jxcore-log( 7149): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT919","peerAvailable":true}]
I/jxcore-log( 7149): 
I/jxcore-log( 7149): Found peer : samsung-SM-G900F_PT919, Available: true
I/jxcore-log( 7149): 
I/jxcore-log( 7149): startWithNextDevice
I/jxcore-log( 7149): 
I/jxcore-log( 7149): device[2]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:53.324Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:53.324Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:53.324Z SendDataConnector.js: do connect now
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 7149): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 7149): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 850)
W/LGMDMUISystemServiceAdapter( 7149): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7149): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3811): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3811): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e348aa0  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3811): btm_acl_created hci_handle=3 link_role=1  transport=1
W/bt-btm  ( 3811): btm_acl_created hci_handle=3 link_role=0  transport=1
W/bt-l2cap( 3811): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3811): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3811): btm_read_remote_version_complete: BDA: 7c-f9-0e-34-8a-a0
,W/bt-btm  ( 3811): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24844
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 24
,W/bt-btm  ( 3811): btm_process_remote_ext_features_page 0: BDA: 7c-f9-0e-34-8a-a0
,W/bt-btm  ( 3811): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3811): btm_process_remote_ext_features_page 1: BDA: 7c-f9-0e-34-8a-a0
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3811): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
W/bt-btif ( 3811): info:x10
D/        ( 3811): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3811): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3811): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3811): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
D/LGBluetoothPowerSaveListener( 7229): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-sdp  ( 3811): process_service_search_attr_rsp
W/bt-l2cap( 3811): L2CA_DisconnectReq()  CID: 0x0043
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3811): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 7cf90e348aa0  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3811): L2CAP - st: CLOSED evt: 21
,I/BluetoothBondStateMachine( 3811): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3811): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3811): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3811): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3811): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3811): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothRemoteDevices( 3811): [BTUI] setTrustState : false
,D/BluetoothAdapterProperties( 3811): Failed to remove device: 7C:F9:0E:34:8A:A0
I/BluetoothBondStateMachine( 3811): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3811): StableState(): Entering Off State
W/bt-btm  ( 3811): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3811): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3811): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0045,PSM: 3,our MTU present:1,our MTU:1691
,W/bt-l2cap( 3811): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3811): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0045,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-btm  ( 3811): btm_acl_role_changed: BDA: 7c-f9-0e-34-8a-a0
W/bt-btm  ( 3811): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3811): tBTM_SEC_DEV:0xa0386218 rs_disc_pending=0
W/bt-btif ( 3811): bta_dm_check_av:0
,W/bt-btif ( 3811): btif_dm_cback : unhandled event (14)
W/bt-btm  ( 3811): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3811): new conn_srvc id:26, app_id:1
W/bt-btif ( 3811): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3811): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3811): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 850)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): onBytesWritten: 77 bytes successfully written (thread ID: 851)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Outgoing connection initialized (*handshake* thread ID: 851)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Exiting thread (thread ID: 850)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Entering thread (ID: 851)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): onBytesRead: Read 81 bytes successfully (thread ID: 851)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7149): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7149): Exiting thread (ID: 851)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/io.jxcore.node.ConnectionHelper( 7149): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7149): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7149): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7149): Entering thread (ID: 852)
D/io.jxcore.node.OutgoingSocketThread( 7149): Server socket local port: 51367
I/io.jxcore.node.OutgoingSocketThread( 7149): Now accepting connections...
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{30c9cd1b type 2 when 566756 android} when 566756
,I/io.jxcore.node.ConnectionHelper( 7149): onListeningForIncomingConnections: Outgoing connection is using port 51367 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 7149): 2016-01-15T18:52:55.997Z SendDataConnector.js: CLIENT connected to 51367, error: null
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:52:55.997Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7149): 
I/io.jxcore.node.OutgoingSocketThread( 7149): Incoming data from address: /127.0.0.1, port: 51367
D/io.jxcore.node.OutgoingSocketThread( 7149): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7149): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7149): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7149): Exiting thread (ID: 852)
I/jxcore-log( 7149): 2016-01-15T18:52:56.006Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7149): 
,D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 854, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7149): Entering thread (ID: 853, name: Sender)
I/wpa_supplicant( 2682): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=203 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1959): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/jxcore-log( 7149): 2016-01-15T18:52:57.513Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:57.752Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7149): 
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7149): 2016-01-15T18:52:58.420Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:52:59.365Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7149): 
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=204 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/btif_config_util( 3811): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=205 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 7149): 2016-01-15T18:52:59.831Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7149): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 120001080a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 120001080a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 120001080a436f72646f7661703270c00c000c01]
,I/jxcore-log( 7149): 2016-01-15T18:53:00.356Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7149): 
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=207 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7149): 2016-01-15T18:53:00.786Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7149): 
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=208 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-38ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=209 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-38ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/jxcore-log( 7149): 2016-01-15T18:53:00.973Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:53:01.389Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:53:01.453Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:53:01.454Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7149): 
I/jxcore-log( 7149): oneRoundDownNow
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): 2016-01-15T18:53:01.462Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:53:01.463Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7149): 
D/io.jxcore.node.ConnectionHelper( 7149): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 7149): close
D/io.jxcore.node.OutgoingSocketThread( 7149): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 854
D/io.jxcore.node.OutgoingSocketThread( 7149): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7149): doStop: Thread ID: 853
D/io.jxcore.node.OutgoingSocketThread( 7149): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 853, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7149): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7149): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7149): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7149): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7149): Either failed to read from the output stream or write to the input stream (thread ID: 854, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7149): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7149): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7149): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 853, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 7149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7149): Exiting thread (ID: 854, name: Receiver)
,I/jxcore-log( 7149): 2016-01-15T18:53:01.490Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7149): 
I/jxcore-log( 7149): ---- round done--------
I/jxcore-log( 7149): 
I/jxcore-log( 7149): startWithNextDevice
I/jxcore-log( 7149): 
W/bt-rfcomm( 3811): rfc_port_closed
W/bt-btif ( 3811): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-l2cap( 3811): L2CA_DisconnectReq()  CID: 0x0044
,I/wpa_supplicant( 2682): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=210 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1959): Event [P2P: Reject scan trigger since one is already pending]
W/bt-l2cap( 3811): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=211 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=212 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 6800010c000a436f72646f7661703270c00c000c01527b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a2273616d73756e672d534d2d47393030465f505433323133222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010c000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
E/bt-btm  ( 3811): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3811): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -2
I/BluetoothMapService( 3811): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3811): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3811): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3811): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3811): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3811): state: -2147483648
D/LGBluetoothPowerSaveListener( 7229): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4625): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4625): Bluetooth Device Name: S5-1
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=214 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577571777387; DSPS: 19066778; Offset : -4316696614
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=215 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=216 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=217 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=219 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 6300010d000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 6300010d000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=220 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 8 6300010d000a436f72646f7661703270c00c000c014d7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a224c47452d4c472d483831355f505434373731222c227261223a2246383a39353a43373a38373a33433a3531227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=221 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=222 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010d000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=223 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2273616d73756e672d534d2d47393030465f5054393139222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86,
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=224 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=225 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=226 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 1200010c0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=227 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=228 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=229 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
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
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213,]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=230 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=231 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010e000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010e000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=232 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6900010e000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2682): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=233 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 120001090a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=234 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/WfdsMonitor( 1959): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac]
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597573881598; DSPS: 19722207; Offset : -4316698271
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=235 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 7 1200010b0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=236 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=237 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=238 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=239 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=240 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
,I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=241 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010a0a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=242 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01],
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=243 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010a0a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=244 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=245 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=246 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G3s-1
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=247 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=248 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1037):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDevi,ceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=249 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010b0a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010b0a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=250 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 8 1200010b0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=251 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=252 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617580741644; DSPS: 20377792; Offset : -4316704524
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=253 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=254 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=255 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=256 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
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
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=257 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139307 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139307 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true,
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=258 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 6900010f000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=259 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001100a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=260 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=261 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2273616d73756e672d534d2d4135303046555f505433373134222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=262 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a2273616d73756e672d534d2d4135303046555f505434373938222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=263 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=264 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=265 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7149): timeout now
I/jxcore-log( 7149): 
I/jxcore-log( 7149): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): sendReportNow
I/jxcore-log( 7149): 
I/jxcore-log( 7149): done, now sending data to server
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:53:58.603Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7149): 
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=266 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=267 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000108000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=268 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000110000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=269 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1471): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1471): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1471): called onTimeUpdated()
I/[SystemUI]Clock( 1471): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
I/[SystemUI]DateView( 1471): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1471): handleTimeUpdate
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=270 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=271 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=272 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
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
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=273 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=274 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 7 1200010b0a436f72646f7661703270c00c000c01]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001110a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=275 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=276 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=277 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 69000111000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2273616d73756e672d534d2d4133303046555f505432303333222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637582655802; DSPS: 21033215; Offset : -4316713182
,I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=278 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=279 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=280 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=281 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=282 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=283 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=56 target=c,om.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=57 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 7149): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service request added successfully
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=284 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2682): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=285 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1959): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2682): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1959): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001120a436f72646f7661703270c00c000c01],
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2682): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1959): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=286 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service discovery started successfully
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000112000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=287 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000112000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 69000112000a436f72646f7661703270c00c000c01537b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a2273616d73756e672d534d2d4133303046555f505437313231222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 7149): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28,
,W/io.jxcore.node.ConnectionHelper( 7149): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=288 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 7 1200010b0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1959): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=289 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=290661309, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2584): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=290661309 [*alarm*], flags=0x0
,I/jxcore-log( 7149): teardown
I/jxcore-log( 7149): 
,I/jxcore-log( 7149): testSendData stopped
I/jxcore-log( 7149): 
I/io.jxcore.node.ConnectionHelper( 7149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7149): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7149): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707438323534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2682): P2P-FIND-STOPPED 
D/WfdsMonitor( 1959): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=290 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): setState: NOT_INITIALIZED
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7149): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7149): setState: NOT_STARTED
I/jxcore-log( 7149): StopBroadcasting went ok
I/jxcore-log( 7149): 
I/jxcore-log( 7149): ****TEST TOOK:  ms ****
I/jxcore-log( 7149): 
I/jxcore-log( 7149): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7149): 
I/jxcore-log( 7149): 2016-01-15T18:54:18.534Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7149): 
,I/io.jxcore.node.ConnectionHelper( 7149): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7149): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7149): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7149): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7149): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/AndroidRuntime( 7850): 
D/AndroidRuntime( 7850): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7850): CheckJNI is OFF
D/AndroidRuntime( 7850): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 7149:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1037): WIN DEATH: Window{777b0f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1037): Skipping PackageSetting{8cc0054 com.example.hello/10319} due to missing metadata
D/WifiService( 1037): Client connection lost with reason: 4
,D/InputDispatcher( 1037): Window went away: Window{777b0f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{1a9a4370 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{4cbeb8 7149:com.test.thalitest/u0a311}, curProc for 7149: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{1a9a4370 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{1a9a4370 u0 com.test.thalitest/.MainActivity t4 f}
,I/art     ( 4625): Explicit concurrent mark sweep GC freed 24372(1251KB) AllocSpace objects, 2(32KB) LOS objects, 34% free, 30MB/46MB, paused 536us total 53.376ms
,I/[LGHome]EVENT( 2081): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2081): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2081): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{8aa70ac co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,I/[LGHome]LGActivityUtil( 2081): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2081): [Launcher.java:1056:onResume()]onResume end
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2081): [Launcher.java:1114:onPause()]onPause
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{2fee9175 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1922): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3725): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1922): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 3725): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3725): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,E/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2024): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3725): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/System.err( 4575): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4575): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4575): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4575): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4575): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4575): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4575): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4575): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4575): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/PostponalbeReceiver( 6687): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 41769(2MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.870ms total 130.883ms
,I/art     ( 1037): WaitForGcToComplete blocked for 89.973ms for cause Explicit
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7882 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2081): , create_time: 1430558575574
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2081): , create_time: 1430558575600
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/GBoardWebViewUtils( 2081): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2081): , create_time: 1452774039338
I/GBoardWebViewUtils( 2081): , expire_time: 0
I/GBoardWebViewUtils( 2081): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2081): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2081): , display: false
I/GBoardWebViewUtils( 2081): , animation: false }
I/[SystemUI]QSlideListController( 1471): onReceive = android.intent.action.PACKAGE_REMOVED
D/WallpaperManager( 2081): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,I/[LGHome]GBoardWebView( 2081): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26a64d4b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1471): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1887): split_name #11 / not available #0
D/SplitUIService( 1887): removed split : 
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/SplitUIManager( 1887): split_name #11 / not available #0
I/SplitUIService( 1887): split app #11
,I/LockScreenSettings( 7882): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/administrator( 1037): Handling package changes for user 0
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [-] updateMediaPlayerInfo
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
I/[LGHome]EVENT( 2081): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
I/[LGHome]EVENT( 2081): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
D/AppUp4:PreloadHelper( 7397): added Exclude : com.test.thalitest
,W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
I/ThermalEngine(  327): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3138): Thermal-Lib-Client: Client request sent
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7904 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/KeyguardModel( 1471): handleShortcutListChanged...
D/KeyguardModel( 1471): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/KeyguardModel( 1471): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  351): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 660us total 10.929ms
,D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
I/ActivityManager( 1037): Killing 6275:com.android.vending/u0a44 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 245us total 11.830ms
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.482ms
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2081): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 6032(322KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/67MB, paused 3.930ms total 240.620ms
I/[Concierge]WidgetView( 2081): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1471): handleShortcutListChanged...
,D/PhoneStatusBar( 1471): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6275/cgroup.procs: No such file or directory
D/[Concierge]Service( 2584): onStartCommand(). Type : 8
D/[Concierge]Service( 2584): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2584): Update widget ID : 11
D/[Concierge]WidgetView( 2081): change position of spinner
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{f48cf5f u0 com.lge.launcher2/.Launcher t3} time:650407
I/[Concierge]WidgetView( 2081): initWebView(). Time : 1452884059618
D/[Concierge]Service( 2584): onStartCommand(). Type : 0
,W/ResourcesManager( 7904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7904): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7904): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7904): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7904): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2081): Return exist ConciergeWebView. Reuse : 492571332
D/[Concierge]WidgetView( 2081): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2081): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@113abe4
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2081): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7850): Shutting down VM
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2081): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2081): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2081): Widget kill message received. Destory myself. My : 1452883436979, New one : 1452884059618
D/[Concierge]WidgetView( 2081): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2081): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/SystemConfig( 7904): BUILD Country: EU
I/SystemConfig( 7904): BUILD Operator: OPEN
I/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2081): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2081): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2081): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2081): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1037): Killing 7266:com.lge.sync/1000 (adj 15): empty #17
,I/Timeline( 2081): Timeline: Activity_idle id: android.os.BinderProxy@1bb923d9 time:650511
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7266/cgroup.procs: No such file or directory
,I/SystemConfig( 7904): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7904): existFile = false
I/SystemConfig( 7904): canReadFile = false
I/SystemConfig( 7904): systemFeature RCS result false
D/SystemConfig( 7904): refreshRcsSupport() :false
I/PackageChangeReceiver( 6783): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2194): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7927 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7927): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/chromium( 2081): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/AppConfig( 7927): Total System Memory = 2995761152
D/SystemHelper( 7927): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1037): Killing 7431:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/GBoardtInterface( 2081): onReloaded()
,I/GBoardWebViewClient( 2081): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2024): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2024): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7431/cgroup.procs: No such file or directory
,D/LIA_Service_LIAService( 2024): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3725): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6687): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3725): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/CoreEventReceiver( 7761): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7229): Not supported Hotkey customization function 
,D/ActionManagerService( 1922): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3725): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3725): onEvent() : ACTION_BOARD_ENABLED
D/HideNavigationAppsReceiver( 7229): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7229): replacing : false
D/HideNavigationAppsReceiver( 7229): Delete mPackageMame : com.test.thalitest
D/ActionManagerService( 1922): notifyUserLog: 1000001
D/ButtonCombinationReceiver( 7229): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7229): replacing : false
V/BoardContentProvider( 3725): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 3725): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3725): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3725): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3725): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,I/UpdateIcingCorporaServi( 4625): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2081): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2081): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,E/SQLiteLog( 4625): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager( 1037): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7954 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 4575): (3850) statement aborts at 11: [INSERT INTO t010(f004,f002,f003) VALUES (?,?,?)] disk I/O error
E/SQLiteDatabase( 4575): Error inserting f004=1828948 f002=1452884059989 f003=62
E/SQLiteDatabase( 4575): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 4575): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 4575): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 4575): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 4575): 	at com.lge.mlt.MltMonitorService.insertResourceInfo(MltMonitorService.java:2996)
E/SQLiteDatabase( 4575): 	at com.lge.mlt.MltMonitorService.access$3200(MltMonitorService.java:38)
E/SQLiteDatabase( 4575): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3451)
E/SQLiteDatabase( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4575): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4575): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,--------- beginning of crash
E/AndroidRuntime( 4625): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4625): Process: com.google.android.googlequicksearchbox:search, PID: 4625
E/AndroidRuntime( 4625): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4625): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4625): 	at csx.d(PG:186)
E/AndroidRuntime( 4625): 	at cun.g(PG:594)
E/AndroidRuntime( 4625): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4625): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 4625): 	at android.content.ContentResolver.update(ContentResolver.java:1349)
E/AndroidRuntime( 4625): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4625): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4625): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4625): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4625): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4625): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4625): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4625): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4625): Sending signal. PID: 4625 SIG: 9
E/DropBoxManagerService( 1037): Can't write: system_app_crash
E/DropBoxManagerService( 1037): java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
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
D/WifiService( 1037): Client connection lost with reason: 4

```
