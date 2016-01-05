#### Test 549702610263d9b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 297794574906; DSPS: 9899043; Offset : -4313256931
,D/AndroidRuntime( 7113): 
D/AndroidRuntime( 7113): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7113): CheckJNI is OFF
D/AndroidRuntime( 7113): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{394e3d29 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{394e3d29 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7133 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7113): Shutting down VM
V/ActivityManager( 1040): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{34bf355a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{1547538b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/art     ( 1040): Explicit concurrent mark sweep GC freed 26032(1140KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.117ms total 133.705ms
,D/ContextHelper( 7133): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7133): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7133): Loading: webviewchromium
I/LibraryLoader( 7133): Time to load native libraries: 4 ms (timestamps 9677-9681)
I/LibraryLoader( 7133): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7133): Binding Chromium to main looper Looper (main, tid 1) {9f85b8a}
I/LibraryLoader( 7133): Expected native library version number "",actual native library version number ""
I/chromium( 7133): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7133): Initializing chromium process, renderers=0
W/art     ( 7133): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  325): registerClient() client 0xb12311a0, uid 10311
,D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@303d886b:true
W/chromium( 7133): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7133): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7133): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7133): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7133): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7133): Build Date: 12/12/14 금
I/Adreno-EGL( 7133): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7133): Remote Branch: 
I/Adreno-EGL( 7133): Local Patches: 
I/Adreno-EGL( 7133): Reconstruct Branch: 
,W/ActivityManager( 1040): Activity pause timeout for ActivityRecord{33a8b8ae u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7133): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7133): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7133): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7133): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7133): CordovaWebView is running on device made by: LGE
,W/art     ( 7133): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7133): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7133): Render dirty regions requested: true
I/OpenGLRenderer( 7133): Initialized EGL, version 1.4
D/OpenGLRenderer( 7133): Enabling debug mode 0
,D/Atlas   ( 7133): Validating map...
D/SplitWindow( 1040): check instance of lgWin Window{ecb40d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7133): LgDataFeature() Constructor: none
,D/LgDataFeature( 7133): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1474): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@735d85c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +849ms (total +927ms)
,I/Timeline( 7133): Timeline: Activity_idle id: android.os.BinderProxy@3c26bb3a time:300183
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{33a8b8ae u0 com.test.thalitest/.MainActivity t4} time:300184
I/chromium( 7133): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7133): 
,D/JsMessageQueue( 7133): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7133): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435086080
D/JX-Cordova( 7133): jxcore cordova android initializing
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
W/jxcore-log( 7133): Initializing JXcore engine
W/jxcore-log( 7133): JXcore engine is ready
,W/jxcore-log( 7133): Starting JXcore engine
W/.test.thalitest( 7133): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8294]" dev="sockfs" ino=8294 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7133): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7133): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8424]" dev="sockfs" ino=8424 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7133): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7133): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33605]" dev="sockfs" ino=33605 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 7133): Background sticky concurrent mark sweep GC freed 125435(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.604ms total 108.457ms
,W/jxcore-log( 7133): Platform android
W/jxcore-log( 7133): 
W/jxcore-log( 7133): Process ARCH arm
W/jxcore-log( 7133): 
,I/jxcore-log( 7133): JXcore Cordova bridge is ready!
I/jxcore-log( 7133): 
W/jxcore-log( 7133): JXcore engine is started
,I/jxcore-log( 7133): Toggling radios to true
I/jxcore-log( 7133): 
,D/BluetoothAdapter( 7133): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=7133, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1040): setWifiEnabled: true pid=7133, uid=10311
,E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=7133, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1040): reconnect pid=7133, uid=10311, packageName=com.test.thalitest
E/WifiNative: ( 1040): [302,555,431 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
I/jxcore-log( 7133): Radios toggled
I/jxcore-log( 7133): 
I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering( 1040): InitialState.processMessage what=4
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1040): DISCONNECT: returned true
,E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7211 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
,D/DhcpStateMachine( 1040): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  321): Clearing all IP addresses on wlan0
V/NativeCrypto( 2124): Read error: ssl=0xaf498e00: I/O error during system call, Connection timed out
V/NativeCrypto( 2124): SSL shutdown failed: ssl=0xaf498e00: I/O error during system call, Broken pipe
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): Dns fail occured do internet check.
D/DSQN    ( 1040): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1040): try Internet connection check
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1040): [302,728,956 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-wlan0( 1040): RECONNECT: returned true
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=302746
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=302746
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): stop dsqn bin
D/DSQN    ( 1040): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1040): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1040): InternetcheckProgress is not set don't send DS quality intent
,D/WifiHS20( 1040): hidePasspointNotification off =false
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=302758  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=302758  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=302765  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1040): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
D/TelephonyNetworkFactory-1( 1868): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.,util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/ResourcesManager( 7211): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=302787  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 7211): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
W/ResourcesManager( 7211): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1040): StoppedState
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.config = ptp_only,adb
D/DhcpStateMachine( 1040): StoppedState{ when=-131ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7211): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7211): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7211): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7251 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6713:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10008/pid_6713/cgroup.procs: No such file or directory
,I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7251): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7211): LgDataFeature() Constructor: none
D/LgDataFeature( 7211): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7275 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1040): Killing 6172:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6172/cgroup.procs: No such file or directory
,W/ResourcesManager( 7275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7275): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7275): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7275): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7275): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7275): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7275): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7275): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7275): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7251): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7275): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7275): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7251): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7251): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7275): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7275): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7275): LgDataFeature() Constructor: none
D/LgDataFeature( 7275): LgDataFeature() Constructor Done, null
,V/SoundPool( 7275): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7275): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7275): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7275): doLoad: loading sample sampleID=1
V/SoundPool( 7275): Start decode
V/MediaPlayer[Native]( 7275): decode(31, 10857164, 17813)
I/QRemote ( 7275): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  325): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  325): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  325): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  325): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  325): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  325): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  325): player type = 3
V/AwesomePlayer(  325): AwesomePlayer create()
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/AwesomePlayer(  325): setAudioSink() 
V/AwesomePlayer(  325): reset_l() 
V/AudioCache(  325): notify(0xb11631c0, 8, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
D/Utils   (  325): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  325): setDataSource_l dataSource
V/LGParserOSAL(  325): SniffLGParser start
D/UEI.SmartControl( 6867): QS Service created
V/LGParserOSAL(  325): MainType:5, SubType=0
V/LGParserOSAL(  325): #### check Mime : application/ogg
V/LGParserOSAL(  325): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  325): Use LGExtractor :application/ogg 
D/QRemote ( 7275): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6867): Service initServices...
D/UEI.SmartControl( 6867): QS start get config
V/LGMDMManager( 7275): Create singleton instance
,V/LGParserOSAL(  325): supported mime: application/ogg
V/AwesomePlayer(  325): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  325): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  325): mBitrate = -1 bits/sec
V/AwesomePlayer(  325): AudioTrack Setting
V/AwesomePlayer(  325): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  325): setAudioSource() 
V/MediaPlayerService(  325): prepare
V/AwesomePlayer(  325): prepareAsync_l() 
V/MediaPlayerService(  325): wait for prepare
V/AwesomePlayer(  325): onPrepareAsyncEvent() 
,V/AwesomePlayer(  325): initAudioDecoder() 
W/Utils   (  325): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  325): isOffloadSupported()
V/AudioPolicyManager(  325): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  325): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  325): isAudioPlaybackHookOn() false
V/AwesomePlayer(  325): getUseOffload() = 0 
V/OMXCodec(  325): OMXCodec::Create
V/OMXCodec(  325): findMatchingCodecs()
V/OMXCodec(  325): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  325): matchingCodecs.size()=1
V/OMXCodec(  325): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  325): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  325): LG Codec Adapter start
V/OMXCodec(  325): OMXCodec Createtor
V/OMXCodec(  325): setComponentRole
V/OMXCodec(  325): configureCodec protected=0
V/LGCodecAdapter(  325): called getLGCodecSpecificData
V/LGCodecOSAL(  325): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  325): Called LGconfigureCodecMETA
V/LGCodecOSAL(  325): Called LGconfigureCodecMSG
V/LGCodecOSAL(  325): Not support LGCodec
V/OMXCodec(  325): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  325): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  325): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  325): Could not offload audio decode, try pcm offload
W/Utils   (  325): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  325): isOffloadSupported()
V/AudioPolicyManager(  325): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  325): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  325): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  325): init()
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  325): allocateBuffers
V/OMXCodec(  325): allocateBuffersOnPort portIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a240 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a290 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a2e0 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a330 on input port
V/OMXCodec(  325): allocateBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a3d0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a5b0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a650 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a7e0 on output port
V/OMXCodec(  325): init() mAsyncCompletion wait!!! 
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  325): init() mAsyncCompletion wait!!! 
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  325): init() ,mAsyncCompletion wait free! 
V/AwesomePlayer(  325): finishAsyncPrepare_l() 
V/AudioCache(  325): notify(0xb11631c0, 5, 0, 0)
V/AudioCache(  325): ignored
V/AudioCache(  325): notify(0xb11631c0, 1, 0, 0)
V/AudioCache(  325): prepared
V/AudioCache(  325): wait - success
V/MediaPlayerService(  325): start
V/AwesomePlayer(  325): play_l() 
V/AwesomePlayer(  325): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  325): createAudioPlayer_l
V/AwesomePlayer(  325): seekAudioIfNecessary_l() 
V/AwesomePlayer(  325): startAudioPlayer_l() 
D/AudioPlayer(  325): start of Playback, useOffload 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  325): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  325): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  325): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971247568
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248048
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248208
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248608
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  325): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  325): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  325): allocateBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a650 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a5b0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb119a3d0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  325): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  325): notify(0xb11631c0, 6, 0, 0)
V/AudioCache(  325): ignored
V/MediaPlayerService(  325): wait for playback complete
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab600000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab601000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab602000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab603000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab604000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab605000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab606000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab607000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab608000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab609000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60a000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60b000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60c000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60d000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60e000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab60f000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab610000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab611000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab612000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab613000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab614000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab615000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab616000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab617000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab618000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab619000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61a000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61b000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61c000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61d000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61e000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab61f000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab620000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab621000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab622000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab623000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab624000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab625000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab626000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab627000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab628000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab629000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62a000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62b000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62c000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62d000, 0xb1242000, 4096)
,V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62e000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab62f000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab630000, 0xb1242000, 4096)
V/AudioCache(  325): write(0xb1242000, 4096)
V/AudioCache(  325): memcpy(0xab631000, 0xb1242000, 4096)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  325): postAudioEOS() 
V/AudioCache(  325): write(0xb1242000, 280)
V/AudioCache(  325): memcpy(0xab632000, 0xb1242000, 280)
V/AwesomePlayer(  325): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  325): onStreamDone
V/AwesomePlayer(  325): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  325): notify(0xb11631c0, 2, 0, 0)
V/AudioCache(  325): playback complete
V/AwesomePlayer(  325): pause_l() 
V/AudioCache(  325): notify(0xb11631c0, 7, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
V/AudioCache(  325): wait - success
V/MediaPlayerService(  325): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  325): Pause Playback at 1068125
V/AwesomePlayer(  325): reset_l() 
V/AudioCache(  325): notify(0xb11631c0, 8, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
D/AudioPlayer(  325): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a330 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a2e0 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a290 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a240 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a3d0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a5b0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb119a650 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  325): AudioPlayer releasing audio source
D/AudioPlayer(  325): AudioPlayer done releasing audio source
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/AwesomePlayer(  325): ~AwesomePlayer call
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/SoundPool( 7275): close(31)
V/SoundPool( 7275): pointer = 0x9fff7000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7275): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3692
,D/DSQN    ( 1040): EVENT_INTERNET_CHECK_ENABLE received
I/UEI.SmartControl( 6867): Supports setup maps: true
D/UEI.SmartControl( 6867): QS start statue = true Error code = 0
I/UEI.SmartControl( 6867): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6867): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6867): ### init IR Blaster...
,D/serial_port( 6867): Configuring serial port
E/UEI.SmartControl( 6867): UEIBLaster setting for 616
I/UEI.SmartControl( 6867): Setting serial record hearder size = 2
I/UEI.SmartControl( 6867): configuring settings for MAXQ616
I/UEI.SmartControl( 6867): Get version...
D/UEI.SmartControl( 6867): serial port data available: 21
,D/UEI.SmartControl( 6867): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6867): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6867): QS saving settings...
,D/UEI.SmartControl( 6867): IR Blaster version: 25672567
D/UEI.SmartControl( 6867): serial port data available: 4
,I/UEI.SmartControl( 6867): Device manager: loading config....
,D/UEI.SmartControl( 6867): ----------- loading internal config...
W/ContextImpl( 6867): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6867): Services init done
D/UEI.SmartControl( 6867): QS Service init finished
D/UEI.SmartControl( 6867): QS Service version name: 2.1.91
D/UEI.SmartControl( 6867): QS Service version code: 201091
D/UEI.SmartControl( 6867): Service requested: Control
E/UEI.SmartControl( 6867): Loading SETTINGS...
D/UEI.SmartControl( 6867): Request IControl service: devices are loaded...
,I/QRemote ( 7275): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6867): ------ IControl API: 11
D/UEI.SmartControl( 6867): File observer start...
E/UEI.SmartControl( 6867): IR Port is disabled: false
D/UEI.SmartControl( 6867): Starting file observer...
I/UEI.SmartControl( 6867): Registering callback...
D/UEI.SmartControl( 6867): Internal service binding...
I/UEI.SmartControl( 6867): ------ IControl API: 19
I/UEI.SmartControl( 6867): Registering Services Ready callback...
D/UEI.SmartControl( 6867): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6867): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6867): -----service ready thread exits
I/QRemote ( 7275): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7275): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7275): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7275): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7275): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6867): ------ IControl API: 8
D/QRemote ( 7275): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7275): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7275): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7275): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7275): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7275): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 7275): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7275): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452015389241]
,D/QRemote ( 7275): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1040): Killing 6191:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7275): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6191/cgroup.procs: No such file or directory
,V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7275): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{3a61f8d4 type 0 when 1452015388072 android} when 1452015388072
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3d7fba7d type 2 when 304709 com.google.android.gms} when 304709
,E/WifiStateMachine( 1040):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:240594] from screen [on:0 period:316443793]
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
,I/wpa_supplicant( 2667): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=304841  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=304849  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2667): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=304953  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=304956  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=304959
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=304963
E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=304964
I/wpa_supplicant( 2667): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2667): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=304968
E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=304968
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=304969  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=304973  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 7211): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : activeList=[]
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7211): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 7211): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=304980  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=304981  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=304982
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=304982
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
,I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1040): Got NetworkAgent Messenger
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1040): NetworkAgent connected
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/CommandListener(  321): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1040): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305031  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305031  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=305032  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305033  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305033  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=305034  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7dd1739 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7dd1739 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
D/CommandListener(  321): Setting iface cfg
D/CommandListener(  321): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2667): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): ignoring duplicate network state non-change
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1040): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 1
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  321): netlink response contains error (File exists)
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
W/dsqn    ( 7339): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7339): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
E/DSQN    ( 7339): DSQN ssw
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7275): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
,D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7275): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7275): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7275): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7251): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7251): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7275): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7275): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7275): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7275): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7275): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
D/LGDataListener(  321): argv[0]=dsqncommand
,D/LGDataListener(  321): argv[1]=wlan0
D/LGDataListener(  321): argv[2]=1
D/LGDataListener(  321): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1040): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 17:36:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452015390374], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452015390355]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1868): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/LgDhcpStateMachineHelper( 1040): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7345): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7345): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7345): version 5.5.6 starting
E/dhcpcd  ( 7345): get_duid: m
D/dhcpcd  ( 7345): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7345): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7345): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7345): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7345): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7345): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7345): wlan0: sending REQUEST (xid 0x5d746e08), next in 4.27 seconds
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1040): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7371 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.916ms
I/art     (  347): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.889ms
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.745ms
,I/AppUp4:AppBoxCP( 7371): onCreate
W/AppUp4:DB( 7371):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7371):  setFingerPrint start
I/AppUp4:DB( 7371):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7371):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7371):  SDK version = 21
I/AppUp4:DB( 7371):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7371): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7371): onReceive
D/LgDataFeature( 7371): LgDataFeature() Constructor: none
D/LgDataFeature( 7371): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7371): Context : android.app.ReceiverRestrictedContext@131ea618
,D/AppUp4:CustFacade( 7371): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7371): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7371): begin check event
I/AppUp4:CustModeStarterReceiver( 7371): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7371): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7371): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7371): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7371): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6738:com.lge.email/u0a23 (adj 15): empty #17
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6738/cgroup.procs: No such file or directory
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524295
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3372): DownloadService onCreate
I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4355): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@be56bbc on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/LGDMClient( 4355): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@6ea5745 on behalf of 3372
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7402 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3372): DownloadService onStartCommand
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@262363cb on behalf of 3372
E/LGDMClient( 4355): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
,V/DownloadManager( 3372): DownloadService onDestroy
D/LGDMClient( 4355): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4355): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ResourcesManager( 7402): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7402): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7402): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7402): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7402): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7402): No package identifier when getting value for resource number 0x00000000
,I/dhcpcd  ( 7345): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/LgDataFeature( 7402): LgDataFeature() Constructor: none
D/LgDataFeature( 7402): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7345): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7345): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7345): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7345): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7345): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7345): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7345): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7345): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/eas_req ( 7402): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7438 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7402): JNI_OnLoad()
I/HubEmail( 7402): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7402): registerNatives()
I/HubEmail( 7402): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7402): registerNativeMethods()
I/HubEmail( 7402): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7402): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager( 1040): Killing 6589:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10004/pid_6589/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
I/LgeMiscReceiver( 3320): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3320): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3320): networkInfo.isConnected() = false
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7472 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7492 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6766:com.android.gallery3d/u0a27 (adj 15): empty #17
,V/FormManager( 7438): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7438): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6766/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Killing 6790:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6790/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7510 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6814:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6814/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/art     ( 7510): Almond Protected OAT
,D/WeatherApplication( 7510): removeAccount
,D/WeatherApplication( 7510): Account.length = 0
E/WeatherApplication( 7510): OPERATOR:OPEN
D/WeatherAncestor( 7510): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:32
D/Weather.Utils( 7510): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7510): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7510): 2 : This is isUpdating : false
D/WeatherAncestor( 7510): connectivity changed - connection : true
D/WeatherService( 7510): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7510): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7510): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7510): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7510): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7510): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:32
,I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7529 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6905:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6905/cgroup.procs: No such file or directory
V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{130f993 type 2 when 308232 android} when 308232
,I/WebViewFactory( 7529): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7529): Loading: webviewchromium
I/LibraryLoader( 7529): Time to load native libraries: 2 ms (timestamps 8406-8408)
I/LibraryLoader( 7529): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7529): Binding Chromium to main looper Looper (main, tid 1) {3eee9563}
,I/LibraryLoader( 7529): Expected native library version number "",actual native library version number ""
I/chromium( 7529): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7529): Initializing chromium process, renderers=0
W/art     ( 7529): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  325): registerClient() client 0xb1427060, uid 10093
,W/chromium( 7529): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 7529): Requires BLUETOOTH permission
I/chromium( 7529): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7529): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7529): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7529): Build Date: 12/12/14 금
I/Adreno-EGL( 7529): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7529): Remote Branch: 
I/Adreno-EGL( 7529): Local Patches: 
I/Adreno-EGL( 7529): Reconstruct Branch: 
,I/NSApplication( 7529): Starting up...
,I/ActivityManager( 1040): Killing 6924:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6924/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3d23872c type 2 when 308793 com.google.android.gms} when 308793
D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7371): onReceive
D/AppUp4:CustFacade( 7371): Context : android.app.ReceiverRestrictedContext@131ea618
D/AppUp4:CustFacade( 7371): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7371): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7371): begin check event
I/AppUp4:CustModeStarterReceiver( 7371): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3372): DownloadService onCreate
I/DownloadManager( 3372): in removeSpuriousFiles
,V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): DownloadService onStartCommand
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@3e0271a7 on behalf of 3372
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@33d57654 on behalf of 3372
D/LGDMClient( 4355): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@34e929fd on behalf of 3372
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LgeMiscReceiver( 3320): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3320): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3320): networkInfo.isConnected() = false
I/LGDMClient( 4355): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/WeatherAncestor( 7510): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:34
D/Weather.Utils( 7510): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7510): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7510): 2 : This is isUpdating : false
D/WeatherAncestor( 7510): connectivity changed - connection : true
D/WeatherService( 7510): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2688a656
D/ForecastDataCache( 7510): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7510): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7510): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7510): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7510): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:34
V/DownloadManager( 3372): processing inserted download 1
,V/DownloadManager( 3372): processing inserted download 4
V/DownloadManager( 3372): processing inserted download 7
W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3372): processing inserted download 8
W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3372): processing inserted download 21
E/LGDMClient( 4355): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4355): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4355): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3372): DownloadService onDestroy
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2366): [AccountUtils] Account not ready
W/Kids    ( 2366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2366): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2366): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
,D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7438): There are no updated forms. The schedule will be deleted.
V/FormManager( 7438): Alarm would be updated, because LastCheckTime has been updated.
D/PostponalbeReceiver( 6678): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6678): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7371): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7371): onReceive
,D/AppUp4:CustFacade( 7371): Context : android.app.ReceiverRestrictedContext@131ea618
D/AppUp4:CustFacade( 7371): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7371): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7371): begin check event
I/AppUp4:CustModeStarterReceiver( 7371): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/UEI.SmartControl( 6867): Internal timer expired: 4
D/UEI.SmartControl( 6867): unbind internal service
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 82666(3MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.038ms total 90.726ms
,D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/serial_port( 6867): close(fd = 24)
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/UEI.SmartControl( 6867): Serial port is closed.
V/DownloadManager( 3372): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4355): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3372): DownloadService onCreate
I/LGDMClient( 4355): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3372): in removeSpuriousFiles
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@16da8143 on behalf of 3372
,W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3320): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3320): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3320): networkInfo.isConnected() = true
D/PhoneState( 3320): setPdpRejectCasuse : false
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3372): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
W/ContextImpl( 4355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3372): in trimDatabase
V/DownloadManager( 3372): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@37a368f9 on behalf of 3372
,D/WeatherAncestor( 7510): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:34
V/DownloadManager( 3372): DownloadService onStartCommand
E/LGDMClient( 4355): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3372): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3372): created cursor android.database.sqlite.SQLiteCursor@1299ee9f on behalf of 3372
D/LGDMClient( 4355): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4355): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3372): processing inserted download 1
V/DownloadManager( 3372): processing inserted download 4
D/Weather.Utils( 7510): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7510): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7510): 2 : This is isUpdating : false
D/WeatherAncestor( 7510): connectivity changed - connection : true
D/WeatherService( 7510): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2688a656
V/DownloadManager( 3372): processing inserted download 7
V/DownloadManager( 3372): processing inserted download 8
,V/DownloadManager( 3372): processing inserted download 9
V/DownloadManager( 3372): processing inserted download 10
V/DownloadManager( 3372): processing inserted download 16
V/DownloadManager( 3372): processing inserted download 17
V/DownloadManager( 3372): processing inserted download 18
V/DownloadManager( 3372): processing inserted download 21
D/ForecastDataCache( 7510): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7510): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7510): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7510): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7510): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:36:34
V/DownloadManager( 3372): DownloadService onDestroy
I/art     ( 2124): Explicit concurrent mark sweep GC freed 44075(2MB) AllocSpace objects, 12(1495KB) LOS objects, 51% free, 30MB/62MB, paused 1.288ms total 80.837ms
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7438): There are no updated forms. The schedule will be deleted.
V/FormManager( 7438): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = mtalk.google.com, class = 1, type = 1
,V/QRemote ( 7275): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7275): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3692
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2366): [AccountUtils] Account not ready
W/Kids    ( 2366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2366): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2366): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
I/BooksSync( 7027): Starting books sync
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc-netbsd(  321): res_queryN name = mtalk.google.com succeed
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/BooksSync( 7027): started syncMyEbooks
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/Kids    ( 2366): [AccountUtils] Account not ready
W/Kids    ( 2366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2366): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2366): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2366): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.google.com, class = 1, type = 1
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  321): res_queryN name = www.google.com succeed
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
,V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
I/jxcore-log( 7133): Test app app.js loaded
I/jxcore-log( 7133): 
,I/chromium( 7133): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7133): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7133): 
,D/GCM     ( 2124): Connected
,D/GCM     ( 2124): Message class com.google.f.a.a.p
I/chromium( 7133): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
W/ApiaryClient( 7027): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2057019576947633655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2057019576947633655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2057019576947633655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
E/BooksSync( 7027): Soft error: 
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2057019576947633655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
,E/BooksSync( 7027): Sync error
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2057019576947633655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
,I/BooksSync( 7027): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 308232, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GAV4    ( 7529): Thread[GAThread,5,main]: No campaign data found.
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 317795999778; DSPS: 10554449; Offset : -4313235424
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 337798212061; DSPS: 11209882; Offset : -4313251237
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2faa2a52 type 2 when 339257 android} when 339257
D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,E/WifiStateMachine( 1040):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1040):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 357801231638; DSPS: 11865341; Offset : -4313252978
,I/jxcore-log( 7133): TAP version 13
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # multiplex can send data
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 1 String should be length:200
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6294): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6294): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6294): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6294): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6294): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6294): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6294): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6294): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = play.googleapis.com, class = 1, type = 1
I/jxcore-log( 7133): # basic
I/jxcore-log( 7133): 
,D/libc-netbsd(  321): res_queryN name = play.googleapis.com succeed
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 2 sane
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 377803495432; DSPS: 12520775; Offset : -4313247173
,I/jxcore-log( 7133): # another
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 3 sane
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 4 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 5 null
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 6 (unnamed assert)
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 7 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 8 should not throw
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 9 (unnamed assert)
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 10 (unnamed assert)
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 11 should not throw
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 12 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 13 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7133): 
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 397805772455; DSPS: 13176210; Offset : -4313259307
,I/jxcore-log( 7133): ok 14 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # failed to get mobile documents path
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 15 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 16 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 17 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 18 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #init should register the networkChanged event
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 417808037708; DSPS: 13831644; Offset : -4313252224
,I/jxcore-log( 7133): ok 19 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #startBroadcasting should throw on null device name
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 20 should throw
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 21 should throw,
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1040): battery changed pluggedType: 2
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3835): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 7133): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 22 should throw
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 23 should throw
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 437810396086; DSPS: 14487081; Offset : -4313243751
,I/jxcore-log( 7133): # #startBroadcasting should throw on negative port
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 24 should throw
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #startBroadcasting should throw on too large port
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1158b0e4 type 2 when 453888 android} when 453888
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
I/jxcore-log( 7133): ok 25 should throw
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 457812232901; DSPS: 15142501; Offset : -4313238043
,I/jxcore-log( 7133): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 26 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 27 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 28 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 29 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 30 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 31 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7133): 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 477814342581; DSPS: 15797930; Offset : -4313234076
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 32 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 33 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 34 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 35 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 36 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 37 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 38 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7133): 
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 497816542209; DSPS: 16453362; Offset : -4313231739
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 39 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 40 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 41 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): ok 42 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 517818834336; DSPS: 17108798; Offset : -4313258948
,I/jxcore-log( 7133): ok 43 should be equal
I/jxcore-log( 7133): 
I/jxcore-log( 7133): ok 44 should be equal
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/jxcore-log( 7133): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7133): 
,I/jxcore-log( 7133): # teardown
I/jxcore-log( 7133): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608396.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608396.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3835): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608396.7133
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608396.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608396.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608396.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@502b9a06 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@502b9a06 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383339362e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383339362e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383339361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383339361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1960): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
I/jxcore-log( 7133): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383339361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383339361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
I/jxcore-log( 7133): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608511.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608511.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608511.7133
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608511.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608511.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608511.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e469925c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e469925c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383531312e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383531312e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383531311f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383531311f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
I/jxcore-log( 7133): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
I/jxcore-log( 7133): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383531311f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608558.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
,D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383531311f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1040): InactiveState{ when=-16ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-17ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-17ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608558.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608558.7133
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608558.7133","ra":"58:3F:54:73:64:C0"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608558.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608558.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dc1b5a06 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dc1b5a06 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383535382e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
I/jxcore-log( 7133): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383535382e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383535381f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383535381f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1040): discovery change broadcast true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383535381f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383535381f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
I/jxcore-log( 7133): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
,D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608602.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/LGWifiP2pService( 1040): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608602.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608602.7133
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608602.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608602.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608602.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b920641a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b920641a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383630322e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383630322e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383630321f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383630321f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/jxcore-log( 7133): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383630321f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383630321f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
D/LGWifiP2pService( 1040): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
I/jxcore-log( 7133): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608636.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetoot,h.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608636.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608636.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608636.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608636.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608636.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80e5e4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@80e5e4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383633362e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383633362e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
,D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383633361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383633361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/jxcore-log( 7133): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383633361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383633361f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/LGWifiP2pService( 1040): remove client information from framework
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
I/jxcore-log( 7133): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608663.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetoot,h.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608663.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608663.7133
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608663.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608663.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608663.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9a4657cc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9a4657cc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383636332e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383636332e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383636331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383636331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
I/jxcore-log( 7133): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDevic,eDiscoverer( 7133): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383636331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383636331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
I/jxcore-log( 7133): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608689.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608689.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.intern,al.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608689.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608689.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608689.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608689.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ebcdf2bc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ebcdf2bc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383638392e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383638392e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383638391f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383638391f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 7133): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383638391f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383638391f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
I/jxcore-log( 7133): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608710.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608710.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608710.7133
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608710.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608710.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608710.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@11503d9a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@11503d9a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383731302e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383731302e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383731301f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383731301f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/jxcore-log( 7133): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383731301f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383731301f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/jxcore-log( 7133): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): remove client information from framework
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608735.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608735.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608735.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608735.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608735.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608735.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@da2b8f4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@da2b8f4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383733352e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383733352e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/jxcore-log( 7133): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383733351f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383733351f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): discovery change broadcast true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/LGWifiP2pService( 1040): P2pEnabledState clear service
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 7133): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383733351f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383733351f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608753.7133
D/LGWifiP2pService( 1040): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): bind: Binding a new listener
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1040): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608753.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7133): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): start: OK
I/io.jxcore.node.ConnectionHelper( 7133): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452015608753.7133
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Waiting for incoming connections...
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7133): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452015608753.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): start: {"pi":"58:3F:54:73:64:C0","pn":"1452015608753.7133","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452015608753.7133","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e650e04c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e650e04c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState add service
D/LGWifiP2pService( 1040): add a new client
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383735332e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323031353630383735332e37313333222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383735331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): start: OK
D/WifiNative-p2p0( 1040): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383735331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/jxcore-log( 7133): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7133): 
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2667): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7133): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/WifiMonitor( 1040): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7133): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7133): onServerStopped
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1040): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7133): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7133): stop: Stopping services
D/LGWifiP2pService( 1040): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7133): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7133): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7133): setState: NOT_STARTED
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1040): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383735331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/jxcore-log( 7133): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7133): 
D/WifiNative-p2p0( 1040): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323031353630383735331f37313333222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1040): remove client information from framework
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1040): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2667): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1040): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1040): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1040): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState clear service request
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): discovery change broadcast false
I/jxcore-log( 7133): # setup
I/jxcore-log( 7133): 
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStat,eChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED,
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED,
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING,
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): setState: STARTED,
I/io.jxcore.node.ConnectionHelper( 7133): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7133): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7133): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7133): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7133): Service requests cleared successfully
,I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX,
I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
,D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1040): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3835): Disconnected process message: 10, size: 0
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 537820926048; DSPS: 17764226; Offset : -4313242433
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 557822805832; DSPS: 18419648; Offset : -4313254791
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{c0d31e9 type 2 when 576608 android} when 576608
D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,I/BooksSync( 7027): Starting books sync
,D/BooksSync( 7027): started syncMyEbooks
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 34323(1853KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.905ms total 99.002ms
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
W/ApiaryClient( 7027): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1997752785337073857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 577825105251; DSPS: 19075083; Offset : -4313244242
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/HttpHelper( 7027): null auth token
W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1997752785337073857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1997752785337073857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
E/BooksSync( 7027): Soft error: 
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1997752785337073857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
,E/BooksSync( 7027): Sync error
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1997752785337073857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
I/BooksSync( 7027): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 576608, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 597827407275; DSPS: 19730518; Offset : -4313230593
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2947470b type 2 when 606812 android} when 606812
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 617829680756; DSPS: 20385953; Offset : -4313246192
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 637832514135; DSPS: 21041406; Offset : -4313250998
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,I/ActivityManager( 1040): Killing 6954:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_6954/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 657841960273; DSPS: 21697075; Offset : -4313234558
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 677844032972; DSPS: 22352503; Offset : -4313237236
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 697845946872; DSPS: 23007926; Offset : -4313245840
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 717848177385; DSPS: 23663359; Offset : -4313243163
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 737849706805; DSPS: 24318769; Offset : -4313239830
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 757852417318; DSPS: 24974218; Offset : -4313245303
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 777854676216; DSPS: 25629652; Offset : -4313244680
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 797856760532; DSPS: 26285080; Offset : -4313235481
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,I/ActivityManager( 1040): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7830 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7830): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7830): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1a3571f5
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
I/ActivityManager( 1040): Killing 6294:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10044/pid_6294/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 817859030211; DSPS: 26940515; Offset : -4313254621
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 837861919527; DSPS: 27595969; Offset : -4313233956
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 857863791290; DSPS: 28251391; Offset : -4313254310
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 877866066439; DSPS: 28906825; Offset : -4313237461
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 897868125546; DSPS: 29562253; Offset : -4313253627
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 917870226216; DSPS: 30217682; Offset : -4313258566
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 937872478499; DSPS: 30873115; Offset : -4313233988
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,W/bt-smp  ( 3835): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3835): Plain text(LSB ~ MSB) = cc 83 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3835): Encrypted text(LSB ~ MSB) = b9 18 c0 bb 26 2f 25 a3 a9 f8 c3 82 8b f2 03 fb 
,W/bt-btm  ( 3835): Stopping oneshot timer
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{880c9e8 type 2 when 942441 com.android.bluetooth} when 942441
D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 957874688961; DSPS: 31528548; Offset : -4313251414
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 977877692755; DSPS: 32184006; Offset : -4313238317
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
,I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 997879967330; DSPS: 32839441; Offset : -4313252456
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1017882631907; DSPS: 33494888; Offset : -4313243012
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1037884574503; DSPS: 34150312; Offset : -4313253437
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1057886789964; DSPS: 34805744; Offset : -4313235345
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1077888958654; DSPS: 35461175; Offset : -4313233455
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1097891501772; DSPS: 36116619; Offset : -4313253788
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2dcad801 type 2 when 1107595 android} when 1107595
D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,I/BooksSync( 7027): Starting books sync
,D/BooksSync( 7027): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
,D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6268250179683637828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7027): null auth token
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6268250179683637828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7027): Authentication error
E/BooksAccountManager( 7027): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7027): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7027): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7027): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7027): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{b3da3c0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7027): Error response from books API: {
W/ApiaryClient( 7027):  "error": {
W/ApiaryClient( 7027):   "errors": [
W/ApiaryClient( 7027):    {
W/ApiaryClient( 7027):     "domain": "global",
W/ApiaryClient( 7027):     "reason": "required",
W/ApiaryClient( 7027):     "message": "Login Required",
W/ApiaryClient( 7027):     "locationType": "header",
W/ApiaryClient( 7027):     "location": "Authorization"
W/ApiaryClient( 7027):    }
W/ApiaryClient( 7027):   ],
W/ApiaryClient( 7027):   "code": 401,
W/ApiaryClient( 7027):   "message": "Login Required"
W/ApiaryClient( 7027):  }
W/ApiaryClient( 7027): }
,W/ApiaryClient( 7027): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6268250179683637828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7027): Headers:
W/ApiaryClient( 7027): accept-encoding: [gzip]
W/ApiaryClient( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7027): gdata-version: 2
E/BooksSync( 7027): Soft error: 
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6268250179683637828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
,E/BooksSync( 7027): Sync error
E/BooksSync( 7027): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7027): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6268250179683637828&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7027): Headers:
E/BooksSync( 7027): accept-encoding: [gzip]
E/BooksSync( 7027): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7027): gdata-version: 2
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7027): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7027): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7027): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7027): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7027): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7027): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7027): {
E/BooksSync( 7027):  "error": {
E/BooksSync( 7027):   "errors": [
E/BooksSync( 7027):    {
E/BooksSync( 7027):     "domain": "global",
E/BooksSync( 7027):     "reason": "required",
E/BooksSync( 7027):     "message": "Login Required",
E/BooksSync( 7027):     "locationType": "header",
E/BooksSync( 7027):     "location": "Authorization"
E/BooksSync( 7027):    }
E/BooksSync( 7027):   ],
E/BooksSync( 7027):   "code": 401,
E/BooksSync( 7027):   "message": "Login Required"
E/BooksSync( 7027):  }
E/BooksSync( 7027): }
E/BooksSync( 7027): 
E/BooksSync( 7027): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7027): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7027): 	... 8 more
I/BooksSync( 7027): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1107595, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1117898113170; DSPS: 36772195; Offset : -4313234135
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1137900939621; DSPS: 37427648; Offset : -4313245819
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3258863 type 2 when 1138462 android} when 1138462
D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1157903120759; DSPS: 38083080; Offset : -4313262051
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
,I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1177905337522; DSPS: 38738512; Offset : -4313242449
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1197907579285; DSPS: 39393946; Offset : -4313259066
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1217909769850; DSPS: 40049377; Offset : -4313235170
,I/UsageStatsService( 1040): User[0] Flushing usage stats to disk
,I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1040): battery changed pluggedType: 2
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3835): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1237911994427; DSPS: 40704810; Offset : -4313238507
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1257914144210; DSPS: 41360241; Offset : -4313255341
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1277916018370; DSPS: 42015662; Offset : -4313242831
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1297918216955; DSPS: 42671094; Offset : -4313241512
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1317920647313; DSPS: 43326534; Offset : -4313252456
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1337922671837; DSPS: 43981960; Offset : -4313242196
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
,I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1357924834381; DSPS: 44637391; Offset : -4313246374
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1377926974633; DSPS: 45292821; Offset : -4313242327
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1397929164105; DSPS: 45948253; Offset : -4313250146
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1417931171285; DSPS: 46603679; Offset : -4313257127
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1437933033726; DSPS: 47259100; Offset : -4313256285
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1457935095332; DSPS: 47914527; Offset : -4313239408
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1477937443605; DSPS: 48569964; Offset : -4313240807
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1497939372088; DSPS: 49225387; Offset : -4313235087
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1517941766872; DSPS: 49880826; Offset : -4313251087
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
,I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1537943999104; DSPS: 50536259; Offset : -4313246690
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1557946117013; DSPS: 51191689; Offset : -4313265012
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1577948040130; DSPS: 51847112; Offset : -4313264502
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1597951383715; DSPS: 52502581; Offset : -4313247333
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1617953348240; DSPS: 53158005; Offset : -4313235907
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1637955283128; DSPS: 53813429; Offset : -4313254118
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1657957520673; DSPS: 54468862; Offset : -4313244487
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1677959627696; DSPS: 55124291; Offset : -4313243124
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1697962514043; DSPS: 55779746; Offset : -4313255921
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,I/DigitalAppWidgetProvider( 7830): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7830): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1a3571f5
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1717964651639; DSPS: 56435176; Offset : -4313254347
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1737966596892; DSPS: 57090600; Offset : -4313262428
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1757968551467; DSPS: 57746024; Offset : -4313261004
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1777970351773; DSPS: 58401443; Offset : -4313261209
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1797972666036; DSPS: 59056878; Offset : -4313235660
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1817974924362; DSPS: 59712312; Offset : -4313235870
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1837977087375; DSPS: 60367743; Offset : -4313239553
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=70425279, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{6f29519 type 2 when 1842471 com.android.bluetooth} when 1842471
,W/bt-smp  ( 3835): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3835): Plain text(LSB ~ MSB) = a7 91 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3835): Encrypted text(LSB ~ MSB) = 3d 2b 4d a4 f3 3f 14 dd 4c 0d ca cb 72 dc 38 f2 
W/bt-btm  ( 3835): Stopping oneshot timer
I/ProcessStatsService( 1040): Prepared write state in 22ms
,I/ProcessStatsService( 1040): Prepared write state in 18ms
,D/[Concierge]Service( 2647): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=70425279 [*alarm*], flags=0x0
,I/ProcessStatsService( 1040): Pruning old procstats: /data/system/procstats/state-2016-01-05-00-01-00.bin
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1857979140023; DSPS: 61023170; Offset : -4313231556
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{90d49de type 2 when 1209526 com.google.android.gms} when 1209526
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{26de47bf type 0 when 1452016706846 com.google.android.gms} when 1452016706846
D/GCM     ( 2124): Message class com.google.f.a.a.i
,D/LocationManagerService( 1040): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2366): Aggregate from 1452014906778 (log), 1452014906778 (data)
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1877981638297; DSPS: 61678612; Offset : -4313235542
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1897983321050; DSPS: 62334028; Offset : -4313261928
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1917985617761; DSPS: 62989463; Offset : -4313253906
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1937987837805; DSPS: 63644896; Offset : -4313261463
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1957989986287; DSPS: 64300326; Offset : -4313249549
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1977991982270; DSPS: 64955751; Offset : -4313237209
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1997993791168; DSPS: 65611171; Offset : -4313259237
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2017995727358; DSPS: 66266594; Offset : -4313245757
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2037997672923; DSPS: 66922018; Offset : -4313253266
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2057999524426; DSPS: 67577439; Offset : -4313263517
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2078001593377; DSPS: 68232866; Offset : -4313239139
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2098003435088; DSPS: 68888287; Offset : -4313258922
,I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
,D/WifiController( 1040): battery changed pluggedType: 2
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3835): Disconnected process message: 10, size: 0
,D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4355): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2118005507372; DSPS: 69543715; Offset : -4313261912
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 2138007788927; DSPS: 70199149; Offset : -4313238528
,TIME-OUT KILL (timeout was 1800000ms)
```
