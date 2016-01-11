#### Test 55613145dd493c6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 257706005336; DSPS: 8585490; Offset : -4316899889
,D/AndroidRuntime( 7172): 
D/AndroidRuntime( 7172): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7172): CheckJNI is OFF
D/AndroidRuntime( 7172): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1936): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1bf58867 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1bf58867 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7193 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7172): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1847): Display #0 changed.
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{1a8a3ae4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{1b24bb4d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7193): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7193): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7193): Loading: webviewchromium
,I/LibraryLoader( 7193): Time to load native libraries: 2 ms (timestamps 4663-4665)
I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7193): Binding Chromium to main looper Looper (main, tid 1) {261aa394}
,I/LibraryLoader( 7193): Expected native library version number "",actual native library version number ""
I/chromium( 7193): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7193): Initializing chromium process, renderers=0
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  327): registerClient() client 0xb165c040, uid 10311
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cfc9b9:true
W/chromium( 7193): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7193): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7193): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7193): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7193): Build Date: 12/12/14 금
I/Adreno-EGL( 7193): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7193): Remote Branch: 
I/Adreno-EGL( 7193): Local Patches: 
I/Adreno-EGL( 7193): Reconstruct Branch: 
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 26069(1154KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.657ms total 94.810ms
,W/chromium( 7193): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7193): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7193): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7193): CordovaWebView is running on device made by: LGE
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7193): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7193): Render dirty regions requested: true
I/OpenGLRenderer( 7193): Initialized EGL, version 1.4
D/OpenGLRenderer( 7193): Enabling debug mode 0
,D/Atlas   ( 7193): Validating map...
,D/SplitWindow( 1036): check instance of lgWin Window{53e2e6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{1dc4a614 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7193): LgDataFeature() Constructor: none
,D/LgDataFeature( 7193): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1480): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1480): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1480):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1480): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27c5f37a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +688ms (total +763ms)
,I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{1dc4a614 u0 com.test.thalitest/.MainActivity t4} time:275224
I/Timeline( 7193): Timeline: Activity_idle id: android.os.BinderProxy@23f819c4 time:275225
D/JsMessageQueue( 7193): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7193): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7193): 
D/jxcore_app_log( 7193): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060992
D/JX-Cordova( 7193): jxcore cordova android initializing
E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7193): Initializing JXcore engine
W/jxcore-log( 7193): JXcore engine is ready
,W/jxcore-log( 7193): Starting JXcore engine
W/.test.thalitest( 7193): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8396]" dev="sockfs" ino=8396 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7193): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7193): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8573]" dev="sockfs" ino=8573 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7193): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7193): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33693]" dev="sockfs" ino=33693 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 7193): Background sticky concurrent mark sweep GC freed 124904(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.631ms total 124.458ms
,W/jxcore-log( 7193): Platform android
W/jxcore-log( 7193): 
W/jxcore-log( 7193): Process ARCH arm
W/jxcore-log( 7193): 
,I/jxcore-log( 7193): JXcore Cordova bridge is ready!
I/jxcore-log( 7193): 
W/jxcore-log( 7193): JXcore engine is started
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 277707237656; DSPS: 9240890; Offset : -4316885695
,I/jxcore-log( 7193): Toggling radios to true
I/jxcore-log( 7193): 
,D/BluetoothAdapter( 7193): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=7193, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=7193, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1036): disconnect pid=7193, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1036): reconnect pid=7193, uid=10311, packageName=com.test.thalitest
,E/WifiNative: ( 1036): [278,799,213 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
I/jxcore-log( 7193): Radios toggled
I/jxcore-log( 7193): 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7193): Received device characteristics:
I/jxcore-log( 7193): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7193): Bluetooth name: G3-1
I/jxcore-log( 7193): Device name: LGE-LG-D855
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Perf Test app loaded loaded
I/jxcore-log( 7193): 
I/jxcore-log( 7193): check test folder
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): found test : ./testFindPeers.js
I/jxcore-log( 7193): 
I/jxcore-log( 7193): found test : ./testSendData.js
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/Tethering( 1036): InitialState.processMessage what=4
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true,
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DhcpStateMachine( 1036): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  323): Clearing all IP addresses on wlan0
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
,V/NativeCrypto( 2066): Read error: ssl=0xaf4d5c00: I/O error during system call, Connection timed out
V/NativeCrypto( 2066): SSL shutdown failed: ssl=0xaf4d5c00: I/O error during system call, Broken pipe
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7269 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1036): [278,907,229 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
I/wpa_supplicant( 2699): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiHS20( 1036): hidePasspointNotification off =false
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1936): handleWifiStateChangedEvent: 0
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=278922
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=278922
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  323): Clearing all IP addresses on wlan0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1036): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=278954  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=278954  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=278959  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=,-1, [] ]
,D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=278971  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1036): Removing idletimer
D/TelephonyNetworkFactory-1( 1847): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
,D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7269): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7269): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/chromium( 7193): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 7193): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7193): 
I/chromium( 7193): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7269): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7269): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7269): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7269): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7269): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7269): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7301 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6752:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6752/cgroup.procs: No such file or directory
,I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7269): LgDataFeature() Constructor: none
,D/LgDataFeature( 7269): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7328 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1036): Killing 6197:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6197/cgroup.procs: No such file or directory
W/ResourcesManager( 7328): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7328): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7328): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7328): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7328): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7328): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7328): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7328): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7328): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7328): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7301): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7328): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7328): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7328): LgDataFeature() Constructor: none
D/LgDataFeature( 7328): LgDataFeature() Constructor Done, null
,V/SoundPool( 7328): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7328): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7328): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 7328): doLoad: loading sample sampleID=1
I/QRemote ( 7328): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,V/SoundPool( 7328): Start decode
V/MediaPlayer[Native]( 7328): decode(32, 10857164, 17813)
V/MediaPlayerService(  327): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  327): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  327): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  327): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  327): player type = 3
V/AwesomePlayer(  327): AwesomePlayer create()
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): setAudioSink() 
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb5474600, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/Utils   (  327): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  327): setDataSource_l dataSource
V/LGParserOSAL(  327): SniffLGParser start
V/LGParserOSAL(  327): MainType:5, SubType=0
V/LGParserOSAL(  327): #### check Mime : application/ogg
V/LGParserOSAL(  327): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  327): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6923): QS Service created
D/QRemote ( 7328): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7328): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6923): Service initServices...
D/UEI.SmartControl( 6923): QS start get config
,V/LGMDMManager( 7328): Create singleton instance
V/LGParserOSAL(  327): supported mime: application/ogg
V/AwesomePlayer(  327): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  327): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  327): mBitrate = -1 bits/sec
V/AwesomePlayer(  327): AudioTrack Setting
V/AwesomePlayer(  327): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  327): setAudioSource() 
V/MediaPlayerService(  327): prepare
V/AwesomePlayer(  327): prepareAsync_l() 
V/MediaPlayerService(  327): wait for prepare
V/AwesomePlayer(  327): onPrepareAsyncEvent() 
V/AwesomePlayer(  327): initAudioDecoder() 
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  327): isAudioPlaybackHookOn() false
V/AwesomePlayer(  327): getUseOffload() = 0 
V/OMXCodec(  327): OMXCodec::Create
V/OMXCodec(  327): findMatchingCodecs()
V/OMXCodec(  327): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  327): matchingCodecs.size()=1
V/OMXCodec(  327): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  327): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  327): LG Codec Adapter start
V/OMXCodec(  327): OMXCodec Createtor
V/OMXCodec(  327): setComponentRole
V/OMXCodec(  327): configureCodec protected=0
V/LGCodecAdapter(  327): called getLGCodecSpecificData
V/LGCodecOSAL(  327): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMSG
V/LGCodecOSAL(  327): Not support LGCodec
V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  327): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  327): Could not offload audio decode, try pcm offload
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  327): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  327): init()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  327): allocateBuffers
V/OMXCodec(  327): allocateBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  327): init() mAsyncCompletion wait!!! 
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  327): init() mAsyncCompletion wait!!! 
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  327): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  327): finishAsyncPrepare_l() 
V/AudioCache(  327): notify(0xb5474600, 5, 0, 0)
V/AudioCache(  327): ignored
V/AudioCache(  327): notify(0xb5474600, 1, 0, 0)
V/AudioCache(  327): prepared
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): start
V/AwesomePlayer(  327): play_l() 
V/AwesomePlayer(  327): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  327): createAudioPlayer_l
V/AwesomePlayer(  327): seekAudioIfNecessary_l() 
V/AwesomePlayer(  327): startAudioPlayer_l() 
D/AudioPlayer(  327): start of Playback, useOffload 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  327): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  327): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  327): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  327): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  327): notify(0xb5474600, 6, 0, 0)
V/AudioCache(  327): ignored
V/MediaPlayerService(  327): wait for playback complete
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab700000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab701000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab702000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab703000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab704000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab705000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab706000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab707000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab708000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab709000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70a000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70b000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70c000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70d000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70e000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab70f000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab710000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab711000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab712000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab713000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab714000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab715000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab716000, 0xb57cd000, 4096)
,V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab717000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab718000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab719000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71a000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71b000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71c000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71d000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71e000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab71f000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab720000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab721000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab722000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab723000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab724000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab725000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab726000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
,V/AudioCache(  327): memcpy(0xab727000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab728000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab729000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72a000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72b000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72c000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72d000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72e000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab72f000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab730000, 0xb57cd000, 4096)
V/AudioCache(  327): write(0xb57cd000, 4096)
V/AudioCache(  327): memcpy(0xab731000, 0xb57cd000, 4096)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  327): postAudioEOS() 
V/AudioCache(  327): write(0xb57cd000, 280)
V/AudioCache(  327): memcpy(0xab732000, 0xb57cd000, 280)
V/AwesomePlayer(  327): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  327): onStreamDone
V/AwesomePlayer(  327): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  327): notify(0xb5474600, 2, 0, 0)
V/AudioCache(  327): playback complete
V/AwesomePlayer(  327): pause_l() 
V/AudioCache(  327): notify(0xb5474600, 7, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  327): Pause Playback at 1068125
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb5474600, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/AudioPlayer(  327): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  327): [OMX.g,oogle.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  327): AudioPlayer releasing audio source
D/AudioPlayer(  327): AudioPlayer done releasing audio source
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): ~AwesomePlayer call
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/SoundPool( 7328): close(32)
V/SoundPool( 7328): pointer = 0x9ffb9000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7328): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2166
I/UEI.SmartControl( 6923): Supports setup maps: true
D/UEI.SmartControl( 6923): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6923): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6923): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6923): ### init IR Blaster...
D/serial_port( 6923): Configuring serial port
E/UEI.SmartControl( 6923): UEIBLaster setting for 616
I/UEI.SmartControl( 6923): Setting serial record hearder size = 2
I/UEI.SmartControl( 6923): configuring settings for MAXQ616
I/UEI.SmartControl( 6923): Get version...
D/UEI.SmartControl( 6923): serial port data available: 21
,D/UEI.SmartControl( 6923): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6923): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6923): QS saving settings...
,D/UEI.SmartControl( 6923): IR Blaster version: 25672567
,D/UEI.SmartControl( 6923): serial port data available: 4
,W/ContextImpl( 6923): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6923): Services init done
D/UEI.SmartControl( 6923): QS Service init finished
D/UEI.SmartControl( 6923): QS Service version name: 2.1.91
D/UEI.SmartControl( 6923): QS Service version code: 201091
D/UEI.SmartControl( 6923): Service requested: Control
I/QRemote ( 7328): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6923): Device manager: loading config....
I/UEI.SmartControl( 6923): ------ IControl API: 11
D/UEI.SmartControl( 6923): File observer start...
D/UEI.SmartControl( 6923): ----------- loading internal config...
E/UEI.SmartControl( 6923): IR Port is disabled: false
D/UEI.SmartControl( 6923): Starting file observer...
I/UEI.SmartControl( 6923): Registering callback...
D/UEI.SmartControl( 6923): Internal service binding...
I/UEI.SmartControl( 6923): ------ IControl API: 19
I/UEI.SmartControl( 6923): Registering Services Ready callback...
,E/UEI.SmartControl( 6923): Loading SETTINGS...
D/UEI.SmartControl( 6923): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6923): Notify AllClients services are ready: 0
,I/QRemote ( 7328): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6923): -----service ready thread exits
D/QRemote ( 7328): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7328): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7328): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7328): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6923): ------ IControl API: 8
D/QRemote ( 7328): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7328): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7328): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7328): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7328): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7328): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 7328): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7328): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7328): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7328): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452517167207]
,D/QRemote ( 7328): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6221:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7328): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6221/cgroup.procs: No such file or directory
,V/QRemote ( 7328): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7328): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2699): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
,E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281053  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281085  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2699): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2699): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2699): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281167  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281169  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281170
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281172
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281172
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281172
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281181
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281182  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281213  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281215  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281217  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281220
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281221
D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
,D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7269): [AUTORUN] sys.usb.config = ptp_only,adb
I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
D/UsbSettingsReceiver( 7269): [AUTORUN] sys.usb.state = ptp_only,adb
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7269): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7269): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7269): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7269): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 7269): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1036): Got NetworkAgent Messenger
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/ConnectivityService( 1036): NetworkAgent connected
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  323): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281272  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
,E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281273  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281273  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1036):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281283  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281283  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281284  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
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
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
,D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18db93d0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18db93d0 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1936): handleWifiStateChangedEvent: 1
,I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1480): mWifiConnected = true, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/Netd    (  323): netlink response contains error (File exists)
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/StatusBar.NetworkController( 1480): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1480): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ],
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
,D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524290
W/dsqn    ( 7413): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7413): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7413): DSQN ssw
,V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7328): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7328): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7328): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7328): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7301): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7301): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 7269): MCCMNC not supported: null
D/QRemote ( 7328): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7328): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGDataListener(  323): argv[0]=dsqncommand
D/LGDataListener(  323): argv[1]=wlan0
D/LGDataListener(  323): argv[2]=1
D/LGDataListener(  323): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QRemote ( 7328): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
I/QRemote ( 7328): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7328): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 12:59:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452517168171], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452517168147]}
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
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524290
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7419): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7419): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7419): version 5.5.6 starting
E/dhcpcd  ( 7419): get_duid: m
D/dhcpcd  ( 7419): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 7419): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1480): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1480): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7419): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7419): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7419): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7419): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7419): wlan0: sending REQUEST (xid 0x304b08d4), next in 4.02 seconds
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7436 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  351): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 392us total 24.383ms
I/art     (  351): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 14.839ms
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 14.234ms
,I/AppUp4:AppBoxCP( 7436): onCreate
W/AppUp4:DB( 7436):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7436):  setFingerPrint start
I/AppUp4:DB( 7436):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7436):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7436):  SDK version = 21
I/AppUp4:DB( 7436):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7436): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7436): onReceive
D/LgDataFeature( 7436): LgDataFeature() Constructor: none
D/LgDataFeature( 7436): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7436): Context : android.app.ReceiverRestrictedContext@26d83632
D/AppUp4:CustFacade( 7436): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7436): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7436): begin check event
I/AppUp4:CustModeStarterReceiver( 7436): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7436): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7436): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7436): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7436): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6783:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6783/cgroup.procs: No such file or directory
,D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3429): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/LGDMClient( 4344): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/DownloadManager( 3429): DownloadService onCreate
,E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1480): CM callback handler got msg 524295
I/LGDMClient( 4344): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3429): in removeSpuriousFiles
,V/DownloadManager( 3429): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@1666e5b6 on behalf of 3429
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3429): in trimDatabase
V/DownloadManager( 3429): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@336bca24 on behalf of 3429
I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7480 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3429): DownloadService onStartCommand
V/DownloadManager( 3429): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@3573a742 on behalf of 3429
,E/LGDMClient( 4344): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4344): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4344): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3429): processing inserted download 1
V/DownloadManager( 3429): processing inserted download 4
V/DownloadManager( 3429): processing inserted download 7
V/DownloadManager( 3429): processing inserted download 8
,V/DownloadManager( 3429): processing inserted download 9
V/DownloadManager( 3429): processing inserted download 10
V/DownloadManager( 3429): processing inserted download 16
V/DownloadManager( 3429): processing inserted download 17
V/DownloadManager( 3429): processing inserted download 18
V/DownloadManager( 3429): processing inserted download 21
V/DownloadManager( 3429): DownloadService onDestroy
,W/ResourcesManager( 7480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7480): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7480): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/dhcpcd  ( 7419): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/LGEmail ( 7480): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7480): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/dhcpcd  ( 7419): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7419): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7419): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7419): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7419): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7419): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7419): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7419): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/ResourceType( 7480): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7480): LgDataFeature() Constructor: none
D/LgDataFeature( 7480): LgDataFeature() Constructor Done, null
,D/eas_req ( 7480): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
I/jxcore-log( 7193): Connected to the server!
I/jxcore-log( 7193): 
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7525 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7480): JNI_OnLoad()
I/HubEmail( 7480): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7480): registerNatives()
I/HubEmail( 7480): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7480): registerNativeMethods()
I/HubEmail( 7480): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7480): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/chromium( 7193): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
I/ActivityManager( 1036): Killing 6665:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6665/cgroup.procs: No such file or directory
,W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3367): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3367): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3367): networkInfo.isConnected() = false
I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7548 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7568 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6813:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6813/cgroup.procs: No such file or directory
,V/FormManager( 7525): There are no updated forms. The schedule will be deleted.
V/FormManager( 7525): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1036): Killing 6834:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7586 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6867:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6834/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=1065408130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6867/cgroup.procs: No such file or directory
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2aa4300f type 2 when 283624 com.google.android.gms} when 283624
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/art     ( 7586): Almond Protected OAT
D/WeatherApplication( 7586): removeAccount
,D/WeatherApplication( 7586): Account.length = 0
E/WeatherApplication( 7586): OPERATOR:OPEN
D/WeatherAncestor( 7586): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:30
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7193): BLE is supported
I/jxcore-log( 7193): 
D/Weather.Utils( 7586): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7586): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7586): 2 : This is isUpdating : false
,D/WeatherAncestor( 7586): connectivity changed - connection : true
D/WeatherService( 7586): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7586): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7586): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7586): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7586): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7586): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:30
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7604 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6950:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6950/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
I/WebViewFactory( 7604): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LibraryLoader( 7604): Loading: webviewchromium
I/LibraryLoader( 7604): Time to load native libraries: 5 ms (timestamps 4446-4451)
I/LibraryLoader( 7604): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7604): Binding Chromium to main looper Looper (main, tid 1) {31de7865}
,I/LibraryLoader( 7604): Expected native library version number "",actual native library version number ""
I/chromium( 7604): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7604): Initializing chromium process, renderers=0
,W/art     ( 7604): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7604): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7604): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7604): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  327): registerClient() client 0xb14fd620, uid 10093
,W/AudioManagerAndroid( 7604): Requires BLUETOOTH permission
I/Adreno-EGL( 7604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7604): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7604): Build Date: 12/12/14 금
I/Adreno-EGL( 7604): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7604): Remote Branch: 
I/Adreno-EGL( 7604): Local Patches: 
I/Adreno-EGL( 7604): Reconstruct Branch: 
,I/NSApplication( 7604): Starting up...
,I/ActivityManager( 1036): Killing 6972:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6972/cgroup.procs: No such file or directory,
,D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7436): onReceive
,D/AppUp4:CustFacade( 7436): Context : android.app.ReceiverRestrictedContext@26d83632
D/AppUp4:CustFacade( 7436): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7436): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7436): begin check event
I/AppUp4:CustModeStarterReceiver( 7436): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3429): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3429): DownloadService onCreate
D/LGDMClient( 4344): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3429): in removeSpuriousFiles
,V/DownloadManager( 3429): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@2ead6490 on behalf of 3429
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/LGDMClient( 4344): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DownloadManager( 3429): in trimDatabase
V/DownloadManager( 3429): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@bd7e189 on behalf of 3429
,D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3367): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3367): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3367): networkInfo.isConnected() = false
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3429): DownloadService onStartCommand
V/DownloadManager( 3429): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 4344): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@302c39bc on behalf of 3429
,V/DownloadManager( 3429): processing inserted download 1
D/WeatherAncestor( 7586): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:31
W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4344): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3429): processing inserted download 4
D/LGDMClient( 4344): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3429): processing inserted download 7
W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Weather.Utils( 7586): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7586): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7586): 2 : This is isUpdating : false
D/WeatherAncestor( 7586): connectivity changed - connection : true
D/WeatherService( 7586): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c86500
D/ForecastDataCache( 7586): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7586): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7586): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7586): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7586): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:31
,V/DownloadManager( 3429): processing inserted download 8
V/DownloadManager( 3429): processing inserted download 9
V/DownloadManager( 3429): processing inserted download 10
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/DownloadManager( 3429): processing inserted download 16
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/Kids    ( 2370): [AccountUtils] Account not ready
W/Kids    ( 2370): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2370): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2370): 	at java.lang.Thread.run(Thread.java:818)
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3429): processing inserted download 17
V/DownloadManager( 3429): processing inserted download 18
V/DownloadManager( 3429): processing inserted download 21
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
V/DownloadManager( 3429): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7525): There are no updated forms. The schedule will be deleted.
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=1065408130 [*alarm*], flags=0x0
V/FormManager( 7525): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7436): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7436): onReceive
D/AppUp4:CustFacade( 7436): Context : android.app.ReceiverRestrictedContext@26d83632
D/AppUp4:CustFacade( 7436): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7436): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7436): begin check event
I/AppUp4:CustModeStarterReceiver( 7436): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/libc-netbsd(  323): res_queryN name = mtalk.google.com succeed
V/DownloadManager( 3429): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3429): DownloadService onCreate
D/LGDMClient( 4344): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3429): in removeSpuriousFiles
I/LGDMClient( 4344): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3429): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@31b2dc9a on behalf of 3429
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3429): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3429): in trimDatabase
V/DownloadManager( 3429): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4344): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@217b09cb on behalf of 3429
I/art     ( 2066): Explicit concurrent mark sweep GC freed 42863(2MB) AllocSpace objects, 12(1495KB) LOS objects, 51% free, 30MB/62MB, paused 721us total 47.244ms
W/ContextImpl( 4344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 82417(3MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.471ms total 99.062ms
,V/DownloadManager( 3429): DownloadService onStartCommand
E/LGDMClient( 4344): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4344): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4344): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3429): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3429): created cursor android.database.sqlite.SQLiteCursor@36522866 on behalf of 3429
W/Settings( 7480): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LgeMiscReceiver( 3367): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3367): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3367): networkInfo.isConnected() = true
D/PhoneState( 3367): setPdpRejectCasuse : false
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3429): processing inserted download 1
V/DownloadManager( 3429): processing inserted download 4
V/DownloadManager( 3429): processing inserted download 7
V/DownloadManager( 3429): processing inserted download 8
V/DownloadManager( 3429): processing inserted download 9
V/DownloadManager( 3429): processing inserted download 10
V/DownloadManager( 3429): processing inserted download 16
,V/DownloadManager( 3429): processing inserted download 17
V/DownloadManager( 3429): processing inserted download 18
V/DownloadManager( 3429): processing inserted download 21
D/WeatherAncestor( 7586): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:31
D/Weather.Utils( 7586): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7586): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7586): 2 : This is isUpdating : false
D/WeatherAncestor( 7586): connectivity changed - connection : true
D/WeatherService( 7586): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c86500
,D/ForecastDataCache( 7586): 2 : lastUpdatedTime: 1430558561343
V/DownloadManager( 3429): DownloadService onDestroy
D/ForecastDataCache( 7586): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7586): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7586): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7586): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:59:31
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/Kids    ( 2370): [AccountUtils] Account not ready
W/Kids    ( 2370): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2370): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2370): 	at java.lang.Thread.run(Thread.java:818)
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/GCM     ( 2066): Connected
,W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/FormManager( 7525): There are no updated forms. The schedule will be deleted.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7525): Alarm would be updated, because LastCheckTime has been updated.
D/GCM     ( 2066): Message class com.google.f.a.a.p
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2370): [AccountUtils] Account not ready
W/Kids    ( 2370): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2370): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2370): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2370): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2370): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6923): Internal timer expired: 4
D/UEI.SmartControl( 6923): unbind internal service
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.google.com, class = 1, type = 1
,D/serial_port( 6923): close(fd = 24)
,I/UEI.SmartControl( 6923): Serial port is closed.
,D/libc-netbsd(  323): res_queryN name = www.google.com succeed
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7604): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 297708930671; DSPS: 9896306; Offset : -4316903826
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{117d3419 type 2 when 302286 android} when 302286
,V/QRemote ( 7328): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7328): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2166
,I/BooksSync( 7077): Starting books sync
,D/BooksSync( 7077): started syncMyEbooks
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7077): null auth token
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7077): Error response from books API: {
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
,W/ApiaryClient( 7077): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8983285163115824172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7077): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7077): Error response from books API: {
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
,W/ApiaryClient( 7077): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8983285163115824172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/HttpHelper( 7077): null auth token
,W/ApiaryClient( 7077): Error response from books API: {
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
,W/ApiaryClient( 7077): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8983285163115824172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
E/BooksSync( 7077): Soft error: 
E/BooksSync( 7077): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8983285163115824172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7077): Headers:
E/BooksSync( 7077): accept-encoding: [gzip]
E/BooksSync( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7077): gdata-version: 2
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7077): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7077): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7077): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7077): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7077): {
E/BooksSync( 7077):  "error": {
E/BooksSync( 7077):   "errors": [
E/BooksSync( 7077):    {
E/BooksSync( 7077):     "domain": "global",
E/BooksSync( 7077):     "reason": "required",
E/BooksSync( 7077):     "message": "Login Required",
E/BooksSync( 7077):     "locationType": "header",
E/BooksSync( 7077):     "location": "Authorization"
E/BooksSync( 7077):    }
E/BooksSync( 7077):   ],
E/BooksSync( 7077):   "code": 401,
E/BooksSync( 7077):   "message": "Login Required"
E/BooksSync( 7077):  }
E/BooksSync( 7077): }
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7077): 	... 8 more
,E/BooksSync( 7077): Sync error
E/BooksSync( 7077): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8983285163115824172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7077): Headers:
E/BooksSync( 7077): accept-encoding: [gzip]
E/BooksSync( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7077): gdata-version: 2
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7077): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7077): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7077): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7077): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7077): {
E/BooksSync( 7077):  "error": {
E/BooksSync( 7077):   "errors": [
E/BooksSync( 7077):    {
E/BooksSync( 7077):     "domain": "global",
E/BooksSync( 7077):     "reason": "required",
E/BooksSync( 7077):     "message": "Login Required",
E/BooksSync( 7077):     "locationType": "header",
E/BooksSync( 7077):     "location": "Authorization"
E/BooksSync( 7077):    }
E/BooksSync( 7077):   ],
E/BooksSync( 7077):   "code": 401,
E/BooksSync( 7077):   "message": "Login Required"
E/BooksSync( 7077):  }
E/BooksSync( 7077): }
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7077): 	... 8 more
I/BooksSync( 7077): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302286, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=1065408130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,I/ActivityManager( 1036): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7774 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7774): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7774): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@7170be7
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=1065408130 [*alarm*], flags=0x0
I/ActivityManager( 1036): Killing 6999:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6999/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 317710846966; DSPS: 10551729; Offset : -4316910112
,E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{5ddcfbb type 2 when 332358 android} when 332358
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 337712847270; DSPS: 11207154; Offset : -4316893398
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 357714273356; DSPS: 11862561; Offset : -4316901795
,I/[SystemUI]LGPowerUI( 1480): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1480): On Skip Timer : true
,D/WifiController( 1036): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1480): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1480): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1936): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1936): Battery Level Remaining: 100%
D/LEDHandler( 1936): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1480): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3831): Disconnected process message: 10, size: 0
D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4344): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6321): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6321): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6321): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6321): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6321): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=1065408130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=1065408130 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 377715976057; DSPS: 12517977; Offset : -4316908000
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 397717876883; DSPS: 13173399; Offset : -4316899265
,I/jxcore-log( 7193): --- start :testFindPeers.js---
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): testFindPeers created [object Object]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): serverPort is 8876
I/jxcore-log( 7193): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7193): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3831): [BTUI] createSocketChannel FD=84 mFd=82
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): start: OK
I/io.jxcore.node.ConnectionHelper( 7193): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7193): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7193): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7193): start: OK
I/jxcore-log( 7193): StartBroadcasting started ok
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7193): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7193): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:7,5:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 7193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 4 device(s) discovered
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7193): 
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-SERV-DISC-RESP 52:55:27:f0:fd:0b 3 58000101000a436f72646f7661703270c00c000c01427b227069223a2233343a46433a45463a31313a41453a3637222c22706e223a224e657875732035222c227261223a2233343a46433a45463a31313a41453a3637227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7193): 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001010a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
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
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: ,Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.,StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=14 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:6f:c9:5d 4 55000101000a436f72646f7661703270c00c000c013f7b227069223a2246383a39353a43373a38373a33433a3531222c22706e223a2247342d31222c227261223a2246383a39353a43373a38373a33433a3531227dc027
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001020a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 417719161666; DSPS: 13828801; Offset : -4316896245
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
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
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001030a436f72646f7661703270c00c000c01]
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=72 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=75 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 437721209003; DSPS: 14484228; Offset : -4316893404
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled,
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=80 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=81 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timesta,mp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=82 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=28 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=85 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=86 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000104000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=90 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=92 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: A5-1
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabl,edState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=93 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=94 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=95 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000105000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7193): 
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000105000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000105000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000105000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 457722992433; DSPS: 15139647; Offset : -4316910719
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=97 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=99 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
E/wpa_supplicant( 2699): WFDS : wfds disabled
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=101 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_metho,ds=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-18ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-18ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-18ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-19ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-19ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-19ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000106000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=108 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 3 56000106000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7193): 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=109 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=110 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 477724906696; DSPS: 15795069; Offset : -4316888468
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=111 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=112 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=114 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=115 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=116 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 67000107000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [B0:C5:59:,3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7193): 
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7193): 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=121 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=122 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A3-1
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
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/wpa_supplicant( 2699): WFDS : wfds disabled,
,E/wpa_supplicant( 2699): WFDS : wfds disabled,
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=124 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001060a436f72646f7661703270c00c000c01
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=125 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=127 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=128 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=129 dispatchEvent: P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=130 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=131 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=132 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=133 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=135 dispatchEvent: P2P-SERV-DISC-REQ 2437 52:55:27:f0:fd:0b 0 3 120001040a436f72646f7661703270c00c000c01
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=139 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 497726742573; DSPS: 16450490; Offset : -4316914137
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=140 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=141 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-14ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-14ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-15ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-15ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=142 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
E/wpa_supplicant( 2699): WFDS : wfds disabled
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 7193): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): timeout now
I/jxcore-log( 7193): 
I/jxcore-log( 7193): weAreDoneNow
I/jxcore-log( 7193): 
I/jxcore-log( 7193): done, now sending data to server
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=144 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=145 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=146 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=147 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=148 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:18:8b:78 0 3 120001060a436f72646f7661703270c00c000c01
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=149 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=150 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=59 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully,
I/wpa_supplicant( 2699): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=153 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001090a436f72646f7661703270c00c000c01]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WifiNative-p2p0( 1036):    returned b6037688
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=154 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=155 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-15ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-16ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-16ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=157 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=158 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
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
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139287 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001070a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001070a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=161 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 3 120001070a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=162 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 517727751472; DSPS: 17105883; Offset : -4316912162
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=163 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=164 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=80 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=165 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=166 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=71 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=71 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b6037688,
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=167 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=168 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 6700010a000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 6700010a000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=169 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 3 6700010a000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7193): teardown
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): testFindPeers stopped
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2699): P2P-FIND-STOPPED 
D/WfdsMonitor( 1936): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=170 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7193): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setState: NOT_STARTED
I/jxcore-log( 7193): StopBroadcasting went ok
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7193): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): remove channel information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service requests cleared successfully
I/chromium( 7193): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7193): --- start :testSendData.js---
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 13
I/jxcore-log( 7193): 
I/jxcore-log( 7193): daya100000
I/jxcore-log( 7193): 
I/jxcore-log( 7193): check server
I/jxcore-log( 7193): 
I/jxcore-log( 7193): serverPort is 48295
I/jxcore-log( 7193): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7193): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): start: OK
I/io.jxcore.node.ConnectionHelper( 7193): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7193): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7193): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=171 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7193): start: OK
I/jxcore-log( 7193): StartBroadcasting started ok
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): Waiting for incoming connections...
I/jxcore-log( 7193): [ { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 7193):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 7193):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 7193):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 7193):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 7193):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 7193):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 7193):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 7193):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 7193):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 7193):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 7193):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 7193):   { address: '08:EC:A9:50:76:27', tryCount: 0 } ]
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): startWithNextDevice
I/jxcore-log( 7193): 
I/jxcore-log( 7193): do fake peer & start
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:31.781Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:31.782Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:31.782Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 7193): 2016-01-11T13:03:31.789Z SendDataTCPServer.js: TCP/IP server is bound to port: 48295
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 827)
,I/io.jxcore.node.ConnectionHelper( 7193): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2699): P2P-FIND-STOPPED 
D/WfdsMonitor( 1936): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=172 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7193): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 7193): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
,W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
,W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3831): [BTUI] connectSocket FD=85 mFd=84
W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): Start timer timeout, starting now...
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=173 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/LGWifiP2pService( 1036): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=174 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=175 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=86 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=176 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=177 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=178 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010b000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 537729594537; DSPS: 17761303; Offset : -4316900439
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionTimeout: [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 7193): 2016-01-11T13:03:46.806Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:03:46.807Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 Nexus 5] timed out
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:46.808Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=179 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=180 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=181 dispatchEvent: P2P-SERV-DISC-REQ 2437 44:80:eb:7b:5a:07 0 7 120001060a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=182 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=183 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/jxcore-log( 7193): 2016-01-11T13:03:51.810Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:03:51.812Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=184 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=185 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3831): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3831): invalid rfc slot id: 8
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 827)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 827)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 827)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 827)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=186 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=187 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010c0a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1036):    returned b60376a0
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=188 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=189 dispatchEvent: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=190 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=92 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=191 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=192 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=193 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010c000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=194 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 5500010c000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
,I/jxcore-log( 7193): 2016-01-11T13:03:56.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:56.830Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:56.831Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:03:56.834Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 829)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7193): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=4 link_role=1  transport=1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
,W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 24841
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 34-fc-ef-11-ae-67
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3831): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3831): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3831): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51f1c76:true
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 672
D/LGBluetoothFeatureConfig( 7269): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7269): [BTUI] FileNotFound: readProperty
D/LGBluetoothUtils( 7269): [BTUI] FileNotFound: storeHashmapFromFile
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0041
,D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 34fcef11ae67  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 21
I/BluetoothBondStateMachine( 3831): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 3831): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3831): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3831): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3831): Entering PendingCommandState State
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7904 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1369bee4:true
,E/ActivityThread( 7904): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7904): No ProfileInfo entries
,I/LG Account v2.2( 7904): isEnabled: false
I/Feature ( 7904): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7904): [Lifetracker]Country: EU
I/Feature ( 7904): [Lifetracker]Operator: OPEN
I/Feature ( 7904): [Lifetracker]Ranking support: false
I/Feature ( 7904): [Lifetracker]Comfort support: false
I/Feature ( 7904): [Lifetracker]Accessory: true
I/Feature ( 7904): [Lifetracker]Health device: true
I/Feature ( 7904): [Lifetracker]Extra Pedometer: false
I/Feature ( 7904): [Lifetracker]Blood glucose device: false
I/Feature ( 7904): [Lifetracker]Device Number: 3
I/ActivityManager( 1036): Killing 6321:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10044/pid_6321/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 3831): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothRemoteDevices( 3831): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3831): Failed to remove device: 34:FC:EF:11:AE:67
I/BluetoothBondStateMachine( 3831): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3831): StableState(): Entering Off State
,W/bt-btm  ( 3831): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0046,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0046,PSM: 3,peer MTU present: 0,peer MTU: 1691
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
,I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
,W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-btif ( 3831): new conn_srvc id:26, app_id:1
W/bt-btif ( 3831): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3831): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3831): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onSocketConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 829)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): onBytesWritten: 63 bytes successfully written (thread ID: 830)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Outgoing connection initialized (*handshake* thread ID: 830)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 829)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7193): Entering thread (ID: 830)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): onBytesRead: Read 66 bytes successfully (thread ID: 830)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Handshake succeeded with [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onHandshakeSucceeded: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7193): Exiting thread (ID: 830)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7193): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 Nexus 5]
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7193): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7193): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7193): Entering thread (ID: 831)
,D/io.jxcore.node.OutgoingSocketThread( 7193): Server socket local port: 55700
,I/io.jxcore.node.OutgoingSocketThread( 7193): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 7193): onListeningForIncomingConnections: Outgoing connection is using port 55700 (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 7193): 2016-01-11T13:04:00.780Z SendDataConnector.js: CLIENT connected to 55700, error: null
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:00.780Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7193): 
,I/io.jxcore.node.OutgoingSocketThread( 7193): Incoming data from address: /127.0.0.1, port: 55700
,D/io.jxcore.node.OutgoingSocketThread( 7193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7193): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7193): Exiting thread (ID: 831)
,D/io.jxcore.node.StreamCopyingThread( 7193): Entering thread (ID: 833, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7193): Entering thread (ID: 832, name: Sender)
,I/jxcore-log( 7193): 2016-01-11T13:04:00.827Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7193): 
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=195 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=196 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
,D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
,D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1,
,D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42,
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
,D/LGWifiP2pService( 1036):  status: 3,
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION,
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=197 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0],
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=198 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1036):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139287 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-13ms what=139283 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-14ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPee,rs: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=97 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.Discover,yManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:55636
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=199 dispatchEvent: P2P-SERV-DISC-REQ 2437 ee:1f:72:63:11:86 0 7 120001090a436f72646f7661703270c00c000c01
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43756
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:31876
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19996
,I/jxcore-log( 7193): 2016-01-11T13:04:02.960Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29166
,I/jxcore-log( 7193): 2016-01-11T13:04:03.138Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7193): 
D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18276
,I/jxcore-log( 7193): 2016-01-11T13:04:03.389Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7193): 
D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7386
,I/jxcore-log( 7193): 2016-01-11T13:04:03.515Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7193): 
D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 7193): 2016-01-11T13:04:03.680Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:03.826Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=200 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7193): 2016-01-11T13:04:03.967Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:03.968Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7193): 
I/jxcore-log( 7193): oneRoundDownNow
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:03.980Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:03.981Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7193): 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 7193): close
D/io.jxcore.node.OutgoingSocketThread( 7193): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7193): doStop: Thread ID: 833
D/io.jxcore.node.OutgoingSocketThread( 7193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7193): doStop: Thread ID: 832
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 7193): Either failed to read from the output stream or write to the input stream (thread ID: 832, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7193): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7193): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7193): Either failed to read from the output stream or write to the input stream (thread ID: 833, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7193): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7193): Exiting thread (ID: 832, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7193): Exiting thread (ID: 833, name: Receiver)
I/jxcore-log( 7193): 2016-01-11T13:04:03.997Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ---- round done--------
I/jxcore-log( 7193): 
I/jxcore-log( 7193): startWithNextDevice
I/jxcore-log( 7193): 
I/jxcore-log( 7193): do fake peer & start
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:03.999Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:04.000Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:04.000Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting t,o null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 834)
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-rfcomm( 3831): rfc_port_closed
,W/bt-btif ( 3831): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3831): BTM_SwitchRole BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): Requested New Role: 0
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0042
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,W/bt-btm  ( 3831): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 34-fc-ef-11-ae-67
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3831): tBTM_SEC_DEV:0xa0376050 rs_disc_pending=1
W/bt-btif ( 3831): bta_dm_check_av:0
W/bt-btm  ( 3831): BTM: Local device role : 0x01
W/bt-btm  ( 3831): BTM: RemBdAddr: 34fcef11ae67
,W/bt-btif ( 3831): btif_dm_cback : unhandled event (14)
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 557732537030; DSPS: 18416759; Offset : -4316887789
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=201 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=202 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010a0a436f72646f7661703270c00c000c01
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=203 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=204 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=205 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=206 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=207 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=102 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1036): Connected BT device : -1
,I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b588a02:true
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: Nexus 5
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=208 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 7 5500010d000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=209 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010d000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010d000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=210 dispatchEvent: P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010d000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP a2:39:f7:70:12:80 7 5600010d000a436f72646f7661703270c00c000c01407b227069223a2246383a39353a43373a38373a38353a3534222c22706e223a224733732d31222c227261223a2246383a39353a43373a38373a38353a3534227dc027]
,D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=1065408130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3e4b8f13 type 2 when 562803 android} when 562803
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=1065408130 [*alarm*], flags=0x0
,I/BooksSync( 7077): Starting books sync
,D/BooksSync( 7077): started syncMyEbooks
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010d000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010d000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=211 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010d000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/art     ( 1036): Explicit concurrent mark sweep GC freed 70881(4MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 2.365ms total 135.659ms
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7077): null auth token
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=212 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
,W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=213 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010b0a436f72646f7661703270c00c000c01
W/bt-btm  ( 3831): btm_acl_created hci_handle=6 link_role=1  transport=1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3831): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3831): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3831): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3831): process_service_search_attr_rsp
,W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0043
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 08eca9507541  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 21
,I/BluetoothBondStateMachine( 3831): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3831): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3831): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3831): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3831): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3831): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothRemoteDevices( 3831): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3831): Failed to remove device: 08:EC:A9:50:75:41
I/BluetoothBondStateMachine( 3831): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3831): StableState(): Entering Off State
W/bt-btm  ( 3831): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0048,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0048,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3831): new conn_srvc id:26, app_id:1
W/bt-btif ( 3831): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3831): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3831): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onSocketConnected: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 834)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): onBytesWritten: 63 bytes successfully written (thread ID: 835)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Outgoing connection initialized (*handshake* thread ID: 835)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 834)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7193): Entering thread (ID: 835)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): onBytesRead: Read 63 bytes successfully (thread ID: 835)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Handshake succeeded with [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onHandshakeSucceeded: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7193): Exiting thread (ID: 835)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnected: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7193): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 7193): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7193): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 7193): Entering thread (ID: 836)
D/io.jxcore.node.OutgoingSocketThread( 7193): Server socket local port: 37494
I/io.jxcore.node.OutgoingSocketThread( 7193): Now accepting connections...
W/ApiaryClient( 7077): Error response from books API: {
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
,W/ApiaryClient( 7077): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1470320176550242533&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
,I/io.jxcore.node.ConnectionHelper( 7193): onListeningForIncomingConnections: Outgoing connection is using port 37494 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 7193): 2016-01-11T13:04:12.167Z SendDataConnector.js: CLIENT connected to 37494, error: null
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:12.168Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7193): 
,I/io.jxcore.node.OutgoingSocketThread( 7193): Incoming data from address: /127.0.0.1, port: 37494
D/io.jxcore.node.OutgoingSocketThread( 7193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 7193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 7193): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7193): Exiting thread (ID: 836)
,D/io.jxcore.node.StreamCopyingThread( 7193): Entering thread (ID: 838, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 7193): Entering thread (ID: 837, name: Sender)
I/jxcore-log( 7193): 2016-01-11T13:04:12.204Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=214 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
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
E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7077): null auth token
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/wpa_supplicant( 2699): WFDS : wfds disabled
,W/ApiaryClient( 7077): Error response from books API: {,
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
W/ApiaryClient( 7077): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1470320176550242533&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:55636
,I/jxcore-log( 7193): 2016-01-11T13:04:13.640Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
,I/jxcore-log( 7193): 2016-01-11T13:04:13.753Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=215 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 7193): 2016-01-11T13:04:13.811Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,I/jxcore-log( 7193): 2016-01-11T13:04:13.931Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,I/wpa_supplicant( 2699): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 2699): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=216 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1036): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=217 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: null
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 0
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 0
D/LGWifiP2pService( 1036):  status: 4
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 7193): 2016-01-11T13:04:14.099Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7193): 
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-17ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139287 arg2=105 target=com,.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=218 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-20ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-20ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-23ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-25ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-25ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-25ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-25ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-26ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-26ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-27ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-27ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-27ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=107 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b,
D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/jxcore-log( 7193): 2016-01-11T13:04:14.246Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 7193): 2016-01-11T13:04:14.375Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7193): 
,D/        ( 3831): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1446
,I/jxcore-log( 7193): 2016-01-11T13:04:14.482Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:14.529Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7193): 
,V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7193): 2016-01-11T13:04:14.614Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.614Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7193): 
I/jxcore-log( 7193): oneRoundDownNow
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.615Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.615Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7193): 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 7193): close
D/io.jxcore.node.OutgoingSocketThread( 7193): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7193): doStop: Thread ID: 838
D/io.jxcore.node.OutgoingSocketThread( 7193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7193): doStop: Thread ID: 837
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7193): Either failed to read from the output stream or write to the input stream (thread ID: 837, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7193): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7193): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 7193): Either failed to read from the output stream or write to the input stream (thread ID: 838, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7193): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7193): Exiting thread (ID: 837, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7193): Exiting thread (ID: 838, name: Receiver)
I/jxcore-log( 7193): 2016-01-11T13:04:14.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ---- round done--------
I/jxcore-log( 7193): 
I/jxcore-log( 7193): startWithNextDevice
I/jxcore-log( 7193): 
I/jxcore-log( 7193): do fake peer & start
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.627Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.627Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:14.628Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7193): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproj,ect.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,W/bt-rfcomm( 3831): rfc_port_closed
W/bt-btif ( 3831): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 839)
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0044
,W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3831): BTM_SwitchRole BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3831): Requested New Role: 0
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2066): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2066): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2066): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2066): 	at android.os.Binder.execTransact(Binder.java:446)
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
,E/BooksAccountManager( 7077): Authentication error
E/BooksAccountManager( 7077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7077): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7077): null auth token
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31b2dc9a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=219 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-btm  ( 3831): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3831): tBTM_SEC_DEV:0xa0376218 rs_disc_pending=1
W/bt-btif ( 3831): bta_dm_check_av:0
W/bt-btif ( 3831): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=220 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
W/bt-btm  ( 3831): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-btm  ( 3831): btm_acl_created hci_handle=8 link_role=0  transport=1,
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3831): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3831): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3831): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 672
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 2
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0045
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3831): invalid rfc slot id: 11
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 839)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 839)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 839)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 7193): 2016-01-11T13:04:15.475Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:15.475Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:15.475Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 839)
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,W/ApiaryClient( 7077): Error response from books API: {
W/ApiaryClient( 7077):  "error": {
W/ApiaryClient( 7077):   "errors": [
W/ApiaryClient( 7077):    {
W/ApiaryClient( 7077):     "domain": "global",
W/ApiaryClient( 7077):     "reason": "required",
W/ApiaryClient( 7077):     "message": "Login Required",
W/ApiaryClient( 7077):     "locationType": "header",
W/ApiaryClient( 7077):     "location": "Authorization"
W/ApiaryClient( 7077):    }
W/ApiaryClient( 7077):   ],
W/ApiaryClient( 7077):   "code": 401,
W/ApiaryClient( 7077):   "message": "Login Required"
W/ApiaryClient( 7077):  }
W/ApiaryClient( 7077): }
,W/ApiaryClient( 7077): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1470320176550242533&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7077): Headers:
W/ApiaryClient( 7077): accept-encoding: [gzip]
W/ApiaryClient( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7077): gdata-version: 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=221 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=222 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
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
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=112 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/BooksSync( 7077): Soft error: 
E/BooksSync( 7077): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1470320176550242533&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7077): Headers:
E/BooksSync( 7077): accept-encoding: [gzip]
E/BooksSync( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7077): gdata-version: 2
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7077): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7077): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7077): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7077): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7077): {
E/BooksSync( 7077):  "error": {
E/BooksSync( 7077):   "errors": [
E/BooksSync( 7077):    {
E/BooksSync( 7077):     "domain": "global",
E/BooksSync( 7077):     "reason": "required",
E/BooksSync( 7077):     "message": "Login Required",
E/BooksSync( 7077):     "locationType": "header",
E/BooksSync( 7077):     "location": "Authorization"
E/BooksSync( 7077):    }
E/BooksSync( 7077):   ],
E/BooksSync( 7077):   "code": 401,
E/BooksSync( 7077):   "message": "Login Required"
E/BooksSync( 7077):  }
E/BooksSync( 7077): }
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7077): 	... 8 more
,E/BooksSync( 7077): Sync error
E/BooksSync( 7077): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7077): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1470320176550242533&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7077): Headers:
E/BooksSync( 7077): accept-encoding: [gzip]
E/BooksSync( 7077): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7077): gdata-version: 2
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7077): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7077): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7077): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7077): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7077): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7077): {
E/BooksSync( 7077):  "error": {
E/BooksSync( 7077):   "errors": [
E/BooksSync( 7077):    {
E/BooksSync( 7077):     "domain": "global",
E/BooksSync( 7077):     "reason": "required",
E/BooksSync( 7077):     "message": "Login Required",
E/BooksSync( 7077):     "locationType": "header",
E/BooksSync( 7077):     "location": "Authorization"
E/BooksSync( 7077):    }
E/BooksSync( 7077):   ],
E/BooksSync( 7077):   "code": 401,
E/BooksSync( 7077):   "message": "Login Required"
E/BooksSync( 7077):  }
E/BooksSync( 7077): }
E/BooksSync( 7077): 
E/BooksSync( 7077): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7077): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7077): 	... 8 more
I/BooksSync( 7077): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 562803, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3831): btm_acl_role_changed: New role: 0
E/bt-btm  ( 3831): tBTM_SEC_DEV:0xa03763e0 rs_disc_pending=0
W/bt-btif ( 3831): bta_dm_check_av:0
W/bt-btm  ( 3831): BTM: Local device role : 0x00
W/bt-btm  ( 3831): BTM: RemBdAddr: 90e7c4f66977
,W/bt-btif ( 3831): btif_dm_cback : unhandled event (14)
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3831): tBTM_SEC_DEV:0xa03763e0 rs_disc_pending=0
W/bt-btif ( 3831): bta_dm_check_av:0
,W/bt-btif ( 3831): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -2
I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 1
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -3
,I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 7193): 2016-01-11T13:04:20.476Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:20.477Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=223 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=224 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=114 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request,
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=225 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010c0a436f72646f7661703270c00c000c01
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=226 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010e0a436f72646f7661703270c00c000c01],
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=227 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 577733951449; DSPS: 19072166; Offset : -4316907227
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=228 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 7193): 2016-01-11T13:04:25.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:25.496Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:25.497Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:25.497Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7193): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 841)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7193): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=229 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=230 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=115 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=116 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139287 arg2=117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=118 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-10ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-11ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-12ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating th,e timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=10 link_role=1  transport=1
W/bt-btm  ( 3831): btm_acl_created hci_handle=10 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3831): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,D/WifiServerServiceExt( 1036): Connected BT device : -2
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0046
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3831): invalid rfc slot id: 12
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 7
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x004a,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x004a,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0047
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3831): invalid rfc slot id: 13
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 841)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 841)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 7193): 2016-01-11T13:04:26.164Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:26.164Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:26.165Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 841)
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=231 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=232 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=233 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1036):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=119 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=120 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/wpa_supplicant( 2699): WFDS : wfds disabled,
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=234 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -3
I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=235 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=236 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=237 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 120001090a436f72646f7661703270c00c000c01
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/jxcore-log( 7193): 2016-01-11T13:04:31.166Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:31.167Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=238 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=239 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=240 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139287 arg2=121 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=122 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=241 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=242 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=243 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010d0a436f72646f7661703270c00c000c01
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 7193): 2016-01-11T13:04:36.171Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:36.186Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:36.187Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:36.188Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7193): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 843)
,W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=244 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=12 link_role=1  transport=1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=12 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3831): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,D/WifiServerServiceExt( 1036): Connected BT device : -2
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x004c,PSM: 1,our MTU present:1,our MTU:672
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=245 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x004c,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0048
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3831): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 843)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 843)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 843)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 7193): 2016-01-11T13:04:37.676Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:37.676Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:37.677Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 843)
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=246 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{319c1fe5 type 2 when 592906 android} when 592906
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=247 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -3
,I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=248 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=249 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/jxcore-log( 7193): 2016-01-11T13:04:42.677Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:42.678Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=250 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=251 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=252 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010e0a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 597745185504; DSPS: 19727894; Offset : -4316903979
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=253 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:76:28 0 7 1200010a0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=254 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=255 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
,I/jxcore-log( 7193): 2016-01-11T13:04:47.691Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:47.692Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:47.693Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:47.694Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7193): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 845)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7193): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
E/wpa_supplicant( 2699): WFDS : wfds disabled
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=256 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=257 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=123 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=124 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_RE,Q b60376a0: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState add service request
,D/WifiP2pManager( 7193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=14 link_role=1  transport=1
W/bt-btm  ( 3831): btm_acl_created hci_handle=14 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3831): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
D/WifiServerServiceExt( 1036): Connected BT device : -2
,W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x004d,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x0049
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3831): invalid rfc slot id: 15
,W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 21
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 7
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x004e,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x004e,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-sdp  ( 3831): process_service_search_attr_rsp
W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x004a
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3831): invalid rfc slot id: 16
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 845)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 845)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 845)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 7193): 2016-01-11T13:04:49.263Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:49.263Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:49.263Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 845)
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=258 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=259 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=260 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 6700010f000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010f000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=261 dispatchEvent: P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010f000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 92:b6:86:43:73:1c 7 5800010f000a436f72646f7661703270c00c000c01427b227069223a2245303a44423a31303a31343a45323a4330222c22706e223a224e6f7465342d31222c227261223a2245303a44423a31303a31343a45323a4330227dc027]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=262 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=263 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139287 arg2=125 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=126 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED ,
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=264 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=265 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
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
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=127 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=128 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1036): Connected BT device : -3
,I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=266 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/jxcore-log( 7193): 2016-01-11T13:04:54.264Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:54.265Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=267 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=268 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=269 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=270 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=271 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=272 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 7193): 2016-01-11T13:04:59.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:04:59.270Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:59.283Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:04:59.284Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 7193): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 847)
W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 90e7c4f66977  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/[SystemUI]TimeTickManager( 1480): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1480): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1480): called onTimeUpdated()
I/[SystemUI]Clock( 1480): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1480): called onTimeUpdated()
,I/[SystemUI]DateView( 1480): called onTimeUpdated()
I/[SystemUI]DateView( 1480): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1480): handleTimeUpdate
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=273 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=16 link_role=1  transport=1
,W/bt-btm  ( 3831): btm_acl_created hci_handle=16 link_role=1  transport=1
W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3831): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
W/bt-btif ( 3831): info:x10
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 3831): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
D/WifiServerServiceExt( 1036): Connected BT device : -2
W/bt-btm  ( 3831): btm_read_remote_version_complete: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-btm  ( 3831): btm_process_remote_ext_features_page 0: BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): ext_features_complt page_num:1 f[0]:x0f, sm4:11, pend:0
W/bt-btm  ( 3831): btm_process_remote_ext_features_page 1: BDA: 90-e7-c4-f6-69-77
W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3831): L2CAP-Upper layer Config_Rsp,Local CID: 0x004b,Remote CID: 0x004f,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 3831): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 3831): L2CAP-peer_Config_Rsp,Local CID: 0x004b,Remote CID: 0x004f,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3831): process_service_search_attr_rsp
,W/bt-l2cap( 3831): L2CA_DisconnectReq()  CID: 0x004b
,W/bt-l2cap( 3831): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3831): invalid rfc slot id: 17
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 847)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 847)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/jxcore-log( 7193): 2016-01-11T13:05:00.747Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:00.747Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): oneRoundDownNow
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:00.749Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7193): 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 847)
I/jxcore-log( 7193): 2016-01-11T13:05:00.760Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ---- round done--------
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 7193): 
I/jxcore-log( 7193): startWithNextDevice
I/jxcore-log( 7193): 
I/jxcore-log( 7193): do fake peer & start
I/jxcore-log( 7193): 
I/jxcore-log( 7193): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:00.763Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:00.763Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:00.763Z SendDataConnector.js: do connect now
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): connect: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 7193): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 849)
,W/LGMDMUISystemServiceAdapter( 7193): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7193): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3831): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3831): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 7cf90e3796ab  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-btm  ( 3831): BTM_SwitchRole BDA: 90-e7-c4-f6-69-77
W/bt-btm  ( 3831): Requested New Role: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 847)
,W/bt-btm  ( 3831): btm_acl_role_changed: BDA: 90-e7-c4-f6-69-77
,W/bt-btm  ( 3831): btm_acl_role_changed: New role: 1
E/bt-btm  ( 3831): tBTM_SEC_DEV:0xa03763e0 rs_disc_pending=1
W/bt-btif ( 3831): bta_dm_check_av:0
W/bt-btm  ( 3831): BTM: Local device role : 0x01
W/bt-btm  ( 3831): BTM: RemBdAddr: 90e7c4f66977
,W/bt-btif ( 3831): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=274 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=275 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=276 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 617747147007; DSPS: 20383318; Offset : -4316895627
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=277 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/bt-btm  ( 3831): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3831): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1036): Connected BT device : -3
,I/BluetoothMapService( 3831): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3831): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3831): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3831): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3831): state: -2147483648
D/LGBluetoothPowerSaveListener( 7269): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4627): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4627): Bluetooth Device Name: HTC One M8s
,I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=278 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: S5-1
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
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=129 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=130 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=279 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001100a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=280 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
D/btif_config_util( 3831): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2699): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1936): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=281 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=282 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=283 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:18:8b:78 7 67000110000a436f72646f7661703270c00c000c01517b227069223a2242303a43353a35393a33463a37353a3639222c22706e223a225468616c692054657374202847616c61787920533529222c227261223a2242303a43353a35393a33463a37353a3639227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000110000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000110000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=284 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 7 55000110000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/bt-l2cap( 3831): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3831): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3831): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3831): invalid rfc slot id: 18
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 849)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Maximum number of allowed retries (0) reached, giving up... (thread ID: 849)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): Exiting thread (thread ID: 849)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB A5-1]
I/jxcore-log( 7193): 2016-01-11T13:05:08.399Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB A5-1] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:08.400Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB A5-1] failed
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:08.400Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7193): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7193): shutdown (thread ID: 849)
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=285 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=286 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=131 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=132 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1036): No p2p device connected
,D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-7ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=287 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=288 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1036):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=133 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=134 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b,
E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7193): onPeerLost: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/io.jxcore.node.ConnectionHelper( 7193): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] removed
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] not available
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=289 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/jxcore-log( 7193): timeout now
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 7193): 
I/jxcore-log( 7193): sendReportNow
I/jxcore-log( 7193): 
I/jxcore-log( 7193): done, now sending data to server
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): 2016-01-11T13:05:11.834Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:11.834Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 7193): 
D/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 7193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7193): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 7193): 2016-01-11T13:05:11.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 7193): 
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=290 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=291 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=292 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010f0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010f0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=293 dispatchEvent: P2P-SERV-DISC-REQ 2437 0a:ec:a9:50:75:42 0 7 1200010f0a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=294 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=295 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=296 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=-13ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-13ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1036):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 4488
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=135 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=136 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=297 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=298 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=137 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=138 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139310 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001110a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=299 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=300 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147477 obj=Device: G4-1
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=139 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=139 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=139 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=140 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=140 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=140 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000111000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000111000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=301 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000111000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
,D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=302 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=303 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1036):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=304 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=141 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=141 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=141 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=142 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=142 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=142 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139287 arg2=143 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139287 arg2=143 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139287 arg2=143 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=144 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=144 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=144 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-4ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-6ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-6ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-6ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-7ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-7ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-8ms what=139283 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-9ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-5ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
E/wpa_supplicant( 2699): WFDS : wfds disabled,
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 637749066791; DSPS: 21038741; Offset : -4316898451
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=305 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=306 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,E/wpa_supplicant( 2699): WFDS : wfds disabled
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=307 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=308 dispatchEvent: P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/LGWifiP2pService( 1036):  deviceAddress: 92:b6:86:43:73:1c
D/LGWifiP2pService( 1036):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1036):  secondary type: null
D/LGWifiP2pService( 1036):  wps: 392
D/LGWifiP2pService( 1036):  grpcapab: 0
D/LGWifiP2pService( 1036):  devcapab: 37
D/LGWifiP2pService( 1036):  status: 3
D/LGWifiP2pService( 1036):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139287 arg2=145 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139287 arg2=145 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139287 arg2=145 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=146 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=146 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=146 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): restart: Restarting...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1036): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139301 arg2=58 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139301 arg2=58 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service request
D/WifiP2pManager( 7193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service request added successfully
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=309 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/wpa_supplicant( 2699): WFDS : wfds disabled
I/wpa_supplicant( 2699): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139310 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139310 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState discover services
D/WifiNative-p2p0( 1036): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001120a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1036):    returned b60376a0
,D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2699): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1936): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=310 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service discovery started successfully
I/wpa_supplicant( 2699): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1036): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=311 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
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
D/WfdsService( 1936): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1936): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139287 arg2=147 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139287 arg2=147 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=139287 arg2=147 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=148 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=148 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=148 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1036): No p2p device connected
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-2ms what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-3ms what=139283 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010a000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a32322,22c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010a000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=312 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 6700010a000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000112000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000112000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=313 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 7 67000112000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7193): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 9 0300011201]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 9 0300011201]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=314 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 9 0300011201
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000112000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000112000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=315 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 7 55000112000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7193): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 7193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
E/wpa_supplicant( 2699): WFDS : wfds disabled
,D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010d0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010d0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=316 dispatchEvent: P2P-SERV-DISC-REQ 2437 92:b6:86:43:73:1c 0 7 1200010d0a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1936): Event [P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=317 dispatchEvent: P2P-SERV-DISC-REQ 2437 7e:f9:0e:37:96:ac 0 7 1200010b0a436f72646f7661703270c00c000c01
,I/jxcore-log( 7193): teardown
I/jxcore-log( 7193): 
,I/jxcore-log( 7193): testSendData stopped
I/jxcore-log( 7193): 
I/io.jxcore.node.ConnectionHelper( 7193): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7193): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7193): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7193): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7193): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139298 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2699): P2P-FIND-STOPPED 
D/WfdsMonitor( 1936): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=318 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/LGWifiP2pService( 1036): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7193): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7193): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7193): setState: NOT_STARTED
I/jxcore-log( 7193): StopBroadcasting went ok
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ****TEST TOOK:  ms ****
I/jxcore-log( 7193): 
I/jxcore-log( 7193): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7193): 
I/jxcore-log( 7193): 2016-01-11T13:05:30.284Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7193): 
,I/io.jxcore.node.ConnectionHelper( 7193): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7193): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7193): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7193): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7193): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 7193): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/AndroidRuntime( 8036): 
D/AndroidRuntime( 8036): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8036): CheckJNI is OFF
D/AndroidRuntime( 8036): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1036): Killing 7193:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1036): WIN DEATH: Window{53e2e6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1036): Client connection lost with reason: 4
D/InputDispatcher( 1036): Window went away: Window{53e2e6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1036): Skipping PackageSetting{3bcc22ea com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{1dc4a614 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  347): DFP En is all cleared set to be enabled,
,W/ActivityManager( 1036): Spurious death for ProcessRecord{14f8aba 7193:com.test.thalitest/u0a311}, curProc for 7193: null
,I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{1dc4a614 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{1dc4a614 u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{2a436602 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2028): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1936): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2028): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1936): topRunningActivity=ActivityInfo{2f533b13 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2028): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1480): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]Launcher.Model( 2028): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3831): [BTUI] [+] updateMediaPlayerInfo
,W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 1990): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3752): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/art     ( 4627): Explicit concurrent mark sweep GC freed 29209(1494KB) AllocSpace objects, 3(48KB) LOS objects, 34% free, 30MB/46MB, paused 608us total 62.710ms
,D/PostponalbeReceiver( 6727): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4571): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4571): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4571): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4571): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4571): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4571): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4571): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4571): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4571): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4571): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
I/ActivityManager( 1036): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8077 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2028): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1901): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3752): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1480): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2028): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2028): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2028): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1901): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3752): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2028): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/SplitUIManager( 1864): split_name #11 / not available #0
D/SplitUIService( 1864): removed split : 
V/BoardContentProvider( 3752): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1480): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1480): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/GBoardWebViewUtils( 2028): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2028): , create_time: 1430558575574
I/GBoardWebViewUtils( 2028): , expire_time: 0
I/GBoardWebViewUtils( 2028): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2028): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2028): , display: false
I/GBoardWebViewUtils( 2028): , animation: false }
I/GBoardWebViewUtils( 2028): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2028): , create_time: 1430558575600
I/GBoardWebViewUtils( 2028): , expire_time: 0
I/GBoardWebViewUtils( 2028): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2028): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2028): , display: false
I/GBoardWebViewUtils( 2028): , animation: false }
I/GBoardWebViewUtils( 2028): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2028): , create_time: 1452175675684
I/GBoardWebViewUtils( 2028): , expire_time: 0
I/GBoardWebViewUtils( 2028): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2028): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2028): , display: false
I/GBoardWebViewUtils( 2028): , animation: false }
I/art     ( 1036): Explicit concurrent mark sweep GC freed 49066(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.890ms total 209.934ms
,I/art     ( 1036): WaitForGcToComplete blocked for 201.029ms for cause Explicit
D/WallpaperManager( 2028): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27c5f37a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2028): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2028): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/SplitUIManager( 1864): split_name #11 / not available #0
I/SplitUIService( 1864): split app #11
I/LockScreenSettings( 8077): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/administrator( 1036): Handling package changes for user 0
,D/KeyguardModel( 1480): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1480): createShortcutInfo...
D/KeyguardModel( 1480): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1480): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1480): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1480): createShortcutInfo...
D/AppUp4:PreloadHelper( 7436): added Exclude : com.test.thalitest
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,D/KeyguardModel( 1480): handleShortcutListChanged...
I/ThermalEngine(  339): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3159): Thermal-Lib-Client: Client request sent
I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8100 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
I/[LGHome]EVENT( 2028): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1480): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1480): createShortcutInfo...
D/KeyguardModel( 1480): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1480): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1480): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1480): createShortcutInfo...
I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1480): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1480): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
,D/PhoneStatusBar( 1480): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1480): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1480):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1480): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1480): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1480): createShortcutInfo...
W/ResourcesManager( 8100): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8100): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8100): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/ActivityManager( 1036): Killing 7301:com.lge.sync/1000 (adj 15): empty #17
,W/ResourcesManager( 8100): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 8100): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 1036): Explicit concurrent mark sweep GC freed 8533(424KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.349ms total 163.339ms
I/[LGHome]Launcher.Model( 2028): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2028): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2028): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2028): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7301/cgroup.procs: No such file or directory
D/KeyguardModel( 1480): handleShortcutListChanged...
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2028): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{10c9f9dd u0 com.lge.launcher2/.Launcher t3} time:644909
I/[Concierge]WidgetView( 2028): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2618): onStartCommand(). Type : 8
D/[Concierge]Service( 2618): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2618): Update widget ID : 11
D/[Concierge]WidgetView( 2028): change position of spinner
I/SystemConfig( 8100): BUILD Country: EU
,I/SystemConfig( 8100): BUILD Operator: OPEN
I/[Concierge]WidgetView( 2028): initWebView(). Time : 1452517531578
D/[Concierge]Service( 2618): onStartCommand(). Type : 0
D/AndroidRuntime( 8036): Shutting down VM
W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WebView( 2028): Return exist ConciergeWebView. Reuse : 1047045780
D/[Concierge]WidgetView( 2028): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2028): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2028): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@37e4691c
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2028): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1036): Killing 7480:com.lge.email/u0a23 (adj 15): empty #17
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2028): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2028): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_7480/cgroup.procs: No such file or directory
,I/SystemConfig( 8100): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8100): existFile = false
I/SystemConfig( 8100): canReadFile = false
I/SystemConfig( 8100): systemFeature RCS result false
D/SystemConfig( 8100): refreshRcsSupport() :false
D/VoicemailCleanupService( 2347): Cleaning up data for package: com.test.thalitest
W/[Concierge]WidgetView( 2028): Widget kill message received. Destory myself. My : 1452516914993, New one : 1452517531578
D/[Concierge]WidgetView( 2028): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2028): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8122 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 2028): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/art     (  351): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.148ms
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.185ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.894ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2028): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2028): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2028): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2028): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 8122): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8122): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/Timeline( 2028): Timeline: Activity_idle id: android.os.BinderProxy@84e9897 time:645081
,I/LGEmail ( 8122): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8122): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 8122): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8122): LgDataFeature() Constructor: none
,D/LgDataFeature( 8122): LgDataFeature() Constructor Done, null
,I/PackageChangeReceiver( 8122): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/chromium( 2028): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1036): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8145 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 7525:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/GBoardtInterface( 2028): onReloaded()
,I/GBoardWebViewClient( 2028): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1036): failed to open /acct/uid_10026/pid_7525/cgroup.procs: No such file or directory
,V/BoardContentProvider( 3752): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3752): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,W/ResourcesManager( 8145): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8145): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8145): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8145): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3752): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3752): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3752): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3752): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3752): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3752): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3752): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2028): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2028): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2028): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2028): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2028): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2028): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 8145): Total System Memory = 2995761152
,D/SystemHelper( 8145): region [EU], country [EU], operator [OPEN], sub-operator []
,E/SharedPreferencesImpl( 8145): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
