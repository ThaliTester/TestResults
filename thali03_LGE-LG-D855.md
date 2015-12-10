#### Test 50650278b86327b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 258288990096; DSPS: 8604794; Offset : -4323478124
,D/AndroidRuntime( 7087): 
D/AndroidRuntime( 7087): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7087): CheckJNI is OFF
D/AndroidRuntime( 7087): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3926fff7 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3926fff7 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7106 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7087): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1857): Display #0 changed.
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{2ad8231a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{18d50e4b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7106): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7106): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7106): Loading: webviewchromium
I/LibraryLoader( 7106): Time to load native libraries: 3 ms (timestamps 6367-6370)
I/LibraryLoader( 7106): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7106): Binding Chromium to main looper Looper (main, tid 1) {1360b94a}
I/LibraryLoader( 7106): Expected native library version number "",actual native library version number ""
,I/chromium( 7106): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7106): Initializing chromium process, renderers=0
W/art     ( 7106): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  320): registerClient() client 0xb1029d00, uid 10311
,W/chromium( 7106): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@274f04c9:true
I/chromium( 7106): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7106): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/Adreno-EGL( 7106): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7106): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7106): Build Date: 12/12/14 금
I/Adreno-EGL( 7106): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7106): Remote Branch: 
I/Adreno-EGL( 7106): Local Patches: 
I/Adreno-EGL( 7106): Reconstruct Branch: 
I/art     ( 1038): Explicit concurrent mark sweep GC freed 27123(1197KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.628ms total 113.506ms
,W/chromium( 7106): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7106): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7106): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7106): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7106): CordovaWebView is running on device made by: LGE
,W/art     ( 7106): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7106): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7106): Render dirty regions requested: true
I/OpenGLRenderer( 7106): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7106): Enabling debug mode 0
,D/Atlas   ( 7106): Validating map...
,W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{27a26e64 u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1038): check instance of lgWin Window{8d6d4fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7106): LgDataFeature() Constructor: none
D/LgDataFeature( 7106): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
,D/PhoneStatusBar( 1445): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3813f22e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +611ms (total +713ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{27a26e64 u0 com.test.thalitest/.MainActivity t4} time:276796
,I/Timeline( 7106): Timeline: Activity_idle id: android.os.BinderProxy@1a4208fa time:276804
I/chromium( 7106): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7106): 
,D/JsMessageQueue( 7106): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7106): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434861312
D/JX-Cordova( 7106): jxcore cordova android initializing
E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 278290946513; DSPS: 9260219; Offset : -4323505090
W/jxcore-log( 7106): Initializing JXcore engine
W/jxcore-log( 7106): JXcore engine is ready
W/jxcore-log( 7106): Starting JXcore engine
W/.test.thalitest( 7106): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7502]" dev="sockfs" ino=7502 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7106): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7106): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8586]" dev="sockfs" ino=8586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7106): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7106): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30465]" dev="sockfs" ino=30465 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7106): Platform android
W/jxcore-log( 7106): 
W/jxcore-log( 7106): Process ARCH arm
W/jxcore-log( 7106): 
,I/jxcore-log( 7106): JXcore Cordova bridge is ready!
I/jxcore-log( 7106): 
W/jxcore-log( 7106): JXcore engine is started
,I/jxcore-log( 7106): Toggling radios to true
I/jxcore-log( 7106): 
,D/BluetoothAdapter( 7106): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7106, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7106, uid=10311
,E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7106, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [280,160,652 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7106, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7106): Radios toggled
I/jxcore-log( 7106): 
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7106): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7106): 
,I/jxcore-log( 7106): Perf Test app loaded loaded
I/jxcore-log( 7106): 
I/jxcore-log( 7106): check test folder
I/jxcore-log( 7106): 
I/jxcore-log( 7106): found test : ./testFindPeers.js
I/jxcore-log( 7106): 
I/jxcore-log( 7106): found test : ./testSendData.js
I/jxcore-log( 7106): 
,I/wpa_supplicant( 2648): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/Tethering( 1038): InitialState.processMessage what=4
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2118): Read error: ssl=0xaf4d6a00: I/O error during system call, Connection timed out
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7187 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2118): SSL shutdown failed: ssl=0xaf4d6a00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [280,280,460 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiHS20( 1038): hidePasspointNotification off =false
I/wpa_supplicant( 2648): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
,E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=280296
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=280297
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/WifiHS20( 1038): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=280346  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=280346  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=280349  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
,W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1857): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1857):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=280357  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/chromium( 7106): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
I/chromium( 7106): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7106): 
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7187): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7187): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7187): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7187): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7187): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7187): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7106): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-172ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7187): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7187): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7187): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7187): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7187): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7187): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7224 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6625:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6625/cgroup.procs: No such file or directory
,I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7224): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7187): LgDataFeature() Constructor: none
D/LgDataFeature( 7187): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7251 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1038): Killing 6094:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6094/cgroup.procs: No such file or directory
,W/ResourcesManager( 7251): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7251): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7251): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7251): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7251): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7251): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7251): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7251): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7251): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7224): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 7251): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7224): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7224): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7251): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7251): LgDataFeature() Constructor: none
D/LgDataFeature( 7251): LgDataFeature() Constructor Done, null
,V/SoundPool( 7251): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7251): load: fd=30, offset=10857164, length=17813, priority=1
,V/SoundPool( 7251): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7251): doLoad: loading sample sampleID=1
I/QRemote ( 7251): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 7251): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6781): QS Service created
V/SoundPool( 7251): Start decode
V/MediaPlayer[Native]( 7251): decode(31, 10857164, 17813)
,V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
V/AwesomePlayer(  320): AwesomePlayer create()
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6781): Service initServices...
D/UEI.SmartControl( 6781): QS start get config
,V/LGMDMManager( 7251): Create singleton instance
,V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
,V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c20b0 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb5474980, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb5474980, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044810928
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c26f0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb5474980, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac300000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac301000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac302000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac303000, 0xb0404000, 4096)
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac304000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac305000, 0xb0404000, 4096)
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac306000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac307000, 0xb0404000, 4096)
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:642
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac308000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac309000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30a000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30b000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30c000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30d000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30e000, 0xb0404000, 4096)
,V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac30f000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac310000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac311000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac312000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac313000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac314000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac315000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac316000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac317000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac318000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac319000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31a000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31b000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31c000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31d000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31e000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac31f000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac320000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac321000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac322000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac323000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac324000, 0xb0404000, 4096)
,V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac325000, 0xb0404000, 4096)
,V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac326000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac327000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac328000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac329000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32a000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32b000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32c000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32d000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32e000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac32f000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac330000, 0xb0404000, 4096)
V/AudioCache(  320): write(0xb0404000, 4096)
V/AudioCache(  320): memcpy(0xac331000, 0xb0404000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb0404000, 280)
,V/AudioCache(  320): memcpy(0xac332000, 0xb0404000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb5474980, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): notify(0xb5474980, 7, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474980, 8, 0, 0)
,V/AudioCache(  320): ignored,
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c26f0 on port 1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
,V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
,V/SoundPool( 7251): close(31)
V/SoundPool( 7251): pointer = 0x9fe39000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6781): Supports setup maps: true
D/UEI.SmartControl( 6781): QS start statue = true Error code = 0
I/UEI.SmartControl( 6781): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6781): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6781): ### init IR Blaster...
,D/serial_port( 6781): Configuring serial port
,E/UEI.SmartControl( 6781): UEIBLaster setting for 616
I/UEI.SmartControl( 6781): Setting serial record hearder size = 2
I/UEI.SmartControl( 6781): configuring settings for MAXQ616
I/UEI.SmartControl( 6781): Get version...
D/UEI.SmartControl( 6781): serial port data available: 21
,D/UEI.SmartControl( 6781): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6781): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6781): QS saving settings...
D/UEI.SmartControl( 6781): IR Blaster version: 25672567
,D/UEI.SmartControl( 6781): serial port data available: 4
,I/UEI.SmartControl( 6781): Device manager: loading config....
,D/UEI.SmartControl( 6781): ----------- loading internal config...
W/ContextImpl( 6781): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6781): Services init done
D/UEI.SmartControl( 6781): QS Service init finished
D/UEI.SmartControl( 6781): QS Service version name: 2.1.91
D/UEI.SmartControl( 6781): QS Service version code: 201091
D/UEI.SmartControl( 6781): Service requested: Control
,E/UEI.SmartControl( 6781): Loading SETTINGS...
D/UEI.SmartControl( 6781): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6781): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6781): Internal service binding...
I/QRemote ( 7251): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6781): ------ IControl API: 11
D/UEI.SmartControl( 6781): File observer start...
E/UEI.SmartControl( 6781): IR Port is disabled: false
D/UEI.SmartControl( 6781): Starting file observer...
,I/UEI.SmartControl( 6781): Registering callback...
I/UEI.SmartControl( 6781): ------ IControl API: 19
I/UEI.SmartControl( 6781): Registering Services Ready callback...
I/UEI.SmartControl( 6781): Notify client services are ready...
I/UEI.SmartControl( 6781): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6781): -----service ready thread exits
I/QRemote ( 7251): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/QRemote ( 7251): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7251): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7251): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7251): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,D/QRemote ( 7251): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6781): ------ IControl API: 8
D/QRemote ( 7251): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7251): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7251): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7251): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7251): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7251): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7251): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7251): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449756871033]
D/QRemote ( 7251): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6120:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7251): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6120/cgroup.procs: No such file or directory
,V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7251): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7251): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2648): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=282458  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=282479  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
I/wpa_supplicant( 2648): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=282570  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=282571  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282571
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282572
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282572
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282581
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282581
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7187): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7187): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7187): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7187): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7187): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7187): [AUTORUN] onReceive() : TetherState Changed=wlan0,
D/UsbSettingsControl( 7187): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5403): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5403): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7336 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7336): onCreate
,W/AppUp4:DB( 7336):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7336):  setFingerPrint start
I/AppUp4:DB( 7336):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7336):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7336):  SDK version = 21
,I/AppUp4:DB( 7336):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7336): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7336): onReceive
D/LgDataFeature( 7336): LgDataFeature() Constructor: none
D/LgDataFeature( 7336): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7336): Context : android.app.ReceiverRestrictedContext@ad299d8
D/AppUp4:CustFacade( 7336): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7336): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7336): begin check event
I/AppUp4:CustModeStarterReceiver( 7336): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7336): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7336): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7336): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7336): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6655:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6655/cgroup.procs: No such file or directory
,D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4264): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7372 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7372): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7372): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7372): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7372): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7372): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7372): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7372): LgDataFeature() Constructor: none
D/LgDataFeature( 7372): LgDataFeature() Constructor Done, null
,D/eas_req ( 7372): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7400 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7372): JNI_OnLoad()
I/HubEmail( 7372): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7372): registerNatives()
I/HubEmail( 7372): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7372): registerNativeMethods()
I/HubEmail( 7372): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7372): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 30.612ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.862ms
I/ActivityManager( 1038): Killing 6509:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 24.170ms
W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6509/cgroup.procs: No such file or directory
,W/Settings( 7372): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3307): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3307): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3307): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7434 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7400): Network not available. Please check & try again.
V/FormManager( 7400): Network unavailable.
,V/FormManager( 7400): Network unavailable.
I/ActivityManager( 1038): Killing 6685:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6685/cgroup.procs: No such file or directory
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7454 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6709:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6709/cgroup.procs: No such file or directory
,I/jxcore-log( 7106): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7106): 
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7474 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6760:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6760/cgroup.procs: No such file or directory
,I/art     ( 7474): Almond Protected OAT
,E/WifiStateMachine( 1038):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1ae9a28e type 0 when 1449756869810 android} when 1449756869810
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2cd5aaaf type 2 when 285310 com.google.android.gms} when 285310
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/WeatherApplication( 7474): removeAccount
D/WeatherApplication( 7474): Account.length = 0
E/WeatherApplication( 7474): OPERATOR:OPEN
,D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:34
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
,D/WeatherAncestor( 7474): connectivity changed - connection : true
D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:34
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7492 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6834:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6834/cgroup.procs: No such file or directory
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=285553  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=285576  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2648): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2648): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=285594  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=285598  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=285599
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=285599
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,W/ContextImpl( 7492): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7492): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7492): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
W/ContextImpl( 7492): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285657  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285658  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=285658  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285660  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285661  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=285661  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
,I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23b57190 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23b57190 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2648): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 1
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/Netd    (  315): netlink response contains error (File exists)
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1857): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1857):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false,, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
W/dsqn    ( 7527): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
W/dsqn    ( 7527): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/DSQN    ( 7527): DSQN ssw
,I/WebViewFactory( 7492): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7492): Loading: webviewchromium
I/LibraryLoader( 7492): Time to load native libraries: 2 ms (timestamps 5891-5893)
I/LibraryLoader( 7492): Expected native library version number "",actual native library version number ""
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
V/WebViewChromiumFactoryProvider( 7492): Binding Chromium to main looper Looper (main, tid 1) {24a29ddd}
W/dhcpcd  ( 7545): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7545): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/LibraryLoader( 7492): Expected native library version number "",actual native library version number ""
I/chromium( 7492): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/dhcpcd  ( 7545): version 5.5.6 starting
E/dhcpcd  ( 7545): get_duid: m
D/dhcpcd  ( 7545): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7545): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/BrowserStartupController( 7492): Initializing chromium process, renderers=0
W/art     ( 7492): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7492): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,I/chromium( 7492): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7492): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  320): registerClient() client 0xb1019ba0, uid 10093
,W/AudioManagerAndroid( 7492): Requires BLUETOOTH permission
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
I/Adreno-EGL( 7492): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7492): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7492): Build Date: 12/12/14 금
I/Adreno-EGL( 7492): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7492): Remote Branch: 
I/Adreno-EGL( 7492): Local Patches: 
I/Adreno-EGL( 7492): Reconstruct Branch: 
,D/dhcpcd  ( 7545): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7545): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7545): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7545): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 7545): wlan0: sending REQUEST (xid 0xe504089a), next in 3.26 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 14:14:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449756875231], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449756875204]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1857): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1857):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/NSApplication( 7492): Starting up...
,I/ActivityManager( 1038): Killing 6858:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7545): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
I/dhcpcd  ( 7545): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 7545): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 7545): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7545): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 7545): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7545): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7545): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7545): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7336): onReceive
,D/AppUp4:CustFacade( 7336): Context : android.app.ReceiverRestrictedContext@ad299d8
D/AppUp4:CustFacade( 7336): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7336): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7336): begin check event
I/AppUp4:CustModeStarterReceiver( 7336): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3350): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3350): DownloadService onCreate
,D/LGDMClient( 4264): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 7372): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/DownloadManager( 3350): in removeSpuriousFiles
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3350): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 4264): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@ab9f37c on behalf of 3350
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3350): in trimDatabase
V/DownloadManager( 3350): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@744a405 on behalf of 3350
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4264): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3350): DownloadService onStartCommand
D/LGDMClient( 4264): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4264): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3350): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@970cb68 on behalf of 3350
V/DownloadManager( 3350): processing inserted download 1
,I/LgeMiscReceiver( 3307): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3307): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3307): networkInfo.isConnected() = false
W/Settings( 7372): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3350): processing inserted download 4
V/DownloadManager( 3350): processing inserted download 7
V/DownloadManager( 3350): processing inserted download 8
V/DownloadManager( 3350): processing inserted download 9
V/DownloadManager( 3350): processing inserted download 10
V/DownloadManager( 3350): processing inserted download 16
,D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:35
V/DownloadManager( 3350): processing inserted download 17
W/Settings( 7372): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3350): processing inserted download 18
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
D/WeatherAncestor( 7474): connectivity changed - connection : true
D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3f792016
V/DownloadManager( 3350): processing inserted download 21
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:35
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3350): DownloadService onDestroy
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/ResourcesManager( 1403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/WifiStateMachine( 1038):  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:221730] from screen [on:0 period:-1942070448]
E/WifiStateMachine( 1038):  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1942070448]
E/WifiStateMachine( 1038): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-127
,D/WifiNative-wlan0( 1038): doBoolean: SCAN TYPE=ONLY
I/wpa_supplicant( 2648): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): SCAN TYPE=ONLY: returned true
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/DhcpStateMachine( 1038): RunningState
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7251): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7251): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7251): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7251): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7224): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7224): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7187): MCCMNC not supported: null
D/QRemote ( 7251): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7251): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7251): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7251): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7251): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/UEI.SmartControl( 6781): Internal timer expired: 2
D/UEI.SmartControl( 6781): unbind internal service
,D/serial_port( 6781): close(fd = 24)
I/UEI.SmartControl( 6781): Serial port is closed.
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524295
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine( 1038):  ConnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
,V/WiFiOffLoadBroadcast( 7187): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
D/WiFiOffLoadBroadcast( 7187): Not supported operator for automatic switch
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7400): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7400): Alarm would be updated, because LastCheckTime has been updated.
,D/GCM     ( 2118): Connected
,D/GCM     ( 2118): Message class com.google.f.a.a.p
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5403): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7336): [onReceive] request level :IDLE....
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:CustModeStarterReceiver( 7336): onReceive
,D/AppUp4:CustFacade( 7336): Context : android.app.ReceiverRestrictedContext@ad299d8
D/AppUp4:CustFacade( 7336): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7336): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7336): begin check event
I/AppUp4:CustModeStarterReceiver( 7336): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3350): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3350): DownloadService onCreate
D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4264): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4264): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4264): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3350): in removeSpuriousFiles
V/DownloadManager( 3350): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@154c1426 on behalf of 3350
,W/ContextImpl( 4264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3350): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,W/Settings( 7372): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4264): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4264): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4264): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3307): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3307): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3307): networkInfo.isConnected() = true
,D/PhoneState( 3307): setPdpRejectCasuse : false
D/WeatherAncestor( 7474): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:38
D/Weather.Utils( 7474): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7474): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7474): 2 : This is isUpdating : false
D/WeatherAncestor( 7474): connectivity changed - connection : true
D/WeatherService( 7474): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3f792016
D/ForecastDataCache( 7474): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7474): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7474): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7474): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7474): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:38
V/FormManager( 7400): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7400): Alarm would be updated, because LastCheckTime has been updated.
,W/Settings( 7372): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2353): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1038): Explicit concurrent mark sweep GC freed 88039(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.559ms total 111.855ms
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3350): in trimDatabase
V/DownloadManager( 3350): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@203b3614 on behalf of 3350
V/DownloadManager( 3350): DownloadService onStartCommand
V/DownloadManager( 3350): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@b554cb2 on behalf of 3350
V/DownloadManager( 3350): processing inserted download 1
,V/DownloadManager( 3350): processing inserted download 4
V/DownloadManager( 3350): processing inserted download 7
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/DownloadManager( 3350): processing inserted download 8
V/DownloadManager( 3350): processing inserted download 9
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3350): processing inserted download 10
V/DownloadManager( 3350): processing inserted download 16
V/DownloadManager( 3350): processing inserted download 17
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
V/DownloadManager( 3350): processing inserted download 18
V/DownloadManager( 3350): processing inserted download 21
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
V/DownloadManager( 3350): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7492): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7106): Connected to the server!
I/jxcore-log( 7106): 
,I/chromium( 7106): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 298293016505; DSPS: 9915646; Offset : -4323479957
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1a7d6a62 type 2 when 298742 android} when 298742
,V/QRemote ( 7251): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 7251): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:642
,I/BooksSync( 6944): Starting books sync
,D/BooksSync( 6944): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5175288254230191744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5175288254230191744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
,D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5175288254230191744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5175288254230191744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5175288254230191744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 298742, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7694 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7694): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7694): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1e31aeb5
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
I/ActivityManager( 1038): Killing 6885:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6885/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 318295266602; DSPS: 10571080; Offset : -4323488188
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{31b06428 type 2 when 328824 android} when 328824
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 338297600812; DSPS: 11226517; Offset : -4323503727
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 358299396586; DSPS: 11881935; Offset : -4323478128
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{58f0541 type 2 when 358849 android} when 358849
,I/BooksSync( 6944): Starting books sync
,D/BooksSync( 6944): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8114711274837146731&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8114711274837146731&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8114711274837146731&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8114711274837146731&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8114711274837146731&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 333193, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6221): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6221): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6221): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6221): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6221): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6221): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6221): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6221): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = ipv4.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = ipv4.google.com succeed
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
E/PlayEventLogger( 6221): Status 503 without retry-after header
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 378301637881; DSPS: 12537369; Offset : -4323495030
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{233bc8fc type 2 when 388925 android} when 388925
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 398310478446; DSPS: 13193019; Offset : -4323504433
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 418312635939; DSPS: 13848449; Offset : -4323483300
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{26998b85 type 2 when 423568 android} when 423568
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 29853(1334KB) AllocSpace objects, 11(1200KB) LOS objects, 33% free, 44MB/66MB, paused 2.753ms total 191.424ms
,I/BooksSync( 6944): Starting books sync
,D/BooksSync( 6944): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2528922530733371531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2528922530733371531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2528922530733371531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2528922530733371531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2528922530733371531&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 423568, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 438314291400; DSPS: 14503863; Offset : -4323475893
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{352b81c7 type 2 when 453635 android} when 453635
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 458316122485; DSPS: 15159283; Offset : -4323475966
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 478317962634; DSPS: 15814704; Offset : -4323497468
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3762): Disconnected process message: 10, size: 0
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 498319880855; DSPS: 16470127; Offset : -4323501647
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 518321789806; DSPS: 17125549; Offset : -4323484889
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 538323834434; DSPS: 17780976; Offset : -4323484886
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{bfb13f4 type 2 when 549241 android} when 549241
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,I/BooksSync( 6944): Starting books sync
,D/BooksSync( 6944): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2118): Explicit concurrent mark sweep GC freed 44167(2MB) AllocSpace objects, 29(4MB) LOS objects, 51% free, 30MB/62MB, paused 1.203ms total 37.901ms
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4073660833486000386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/HttpHelper( 6944): null auth token
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4073660833486000386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4073660833486000386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4073660833486000386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4073660833486000386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 549241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 558325664166; DSPS: 18436396; Offset : -4323486287
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 578327778117; DSPS: 19091825; Offset : -4323477971
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2866b63e type 2 when 579469 android} when 579469
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 598329652692; DSPS: 19747247; Offset : -4323495486
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 618331930289; DSPS: 20402681; Offset : -4323476189
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 638333740594; DSPS: 21058101; Offset : -4323496836
,I/ActivityManager( 1038): Killing 6221:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6221/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 658335825065; DSPS: 21713529; Offset : -4323487690
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 678337715422; DSPS: 22368951; Offset : -4323489371
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 698339308331; DSPS: 23024363; Offset : -4323483375
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 718342064209; DSPS: 23679814; Offset : -4323504519
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 738344251910; DSPS: 24335245; Offset : -4323483566
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 758346366954; DSPS: 24990675; Offset : -4323504960
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 778348593301; DSPS: 25646108; Offset : -4323506294
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 798351503554; DSPS: 26301563; Offset : -4323495288
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3136ac9f type 2 when 796600 android} when 796600
I/ActivityManager( 1038): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7868 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{3eda21ec type 0 when 1449757294316 com.android.vending} when 1449757294316
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,I/BooksSync( 6944): Starting books sync
D/BooksSync( 6944): started syncMyEbooks
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/LgDataFeature( 7868): LgDataFeature() Constructor: none
,D/LgDataFeature( 7868): LgDataFeature() Constructor Done, null
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,D/Finsky  ( 7868): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4683152956430926126&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
I/ActivityManager( 1038): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7929 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7868): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7868): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7929): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7929): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7868): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/Finsky  ( 7868): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7868): [1] 2.run: Finished loading 1 libraries.
,V/DownloadManager( 3350): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3350): created cursor android.database.sqlite.SQLiteCursor@369f9f80 on behalf of 7868
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7929): VM with version 2.1.0 has multidex support
I/MultiDex( 7929): install
I/MultiDex( 7929): VM has multidex support, MultiDex support library is disabled.
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 31791(1378KB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 1.903ms total 109.861ms
,D/Finsky  ( 7868): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 7929): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Finsky  ( 7868): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 7929): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7929): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b284ebd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7929): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2118): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2118): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2353): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1038): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7970 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationInitializer( 2353): Restart initialization of location
,W/Finsky  ( 7868): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7970): VM with version 2.1.0 has multidex support
I/MultiDex( 7970): install
I/MultiDex( 7970): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7970): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/Finsky  ( 7868): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ActivityThread( 7970): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7970): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b284ebd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7970): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2118): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2118): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2353): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7970): callingUid 10005, callindPid: 7970
D/LocationInitializer( 2353): Restart initialization of location
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
E/MDM     ( 1822): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/MDM     ( 1822): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/Finsky  ( 7868): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{3db79fb0 type 0 when 1449757404384 com.android.vending} when 1449757404384
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7868): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7868): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7868): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7868): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4683152956430926126&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
D/Finsky  ( 7868): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DeviceConnectionService( 1822): client connected with version: 7571000
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7868): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2118): Explicit concurrent mark sweep GC freed 30384(1748KB) AllocSpace objects, 11(1584KB) LOS objects, 51% free, 30MB/62MB, paused 2.263ms total 62.921ms
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7868): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7868): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7868): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7868): [1] DailyHygiene.reschedule: Scheduling new run in 91 minutes (failures=3)
D/DeviceConnectionService( 1822): client connected with version: 7571000
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1403): Notification difference=198
,D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4683152956430926126&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4683152956430926126&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4683152956430926126&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
I/ActivityManager( 1038): Killing 7224:com.lge.sync/1000 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 796600, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7224/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 818353649692; DSPS: 26956993; Offset : -4323485406
,I/ActivityManager( 1038): Killing 7187:com.android.settings/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7187/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 7336:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_7336/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1bda2f46 type 0 when 1449757419798 com.android.vending} when 1449757419798
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7868): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 838355889736; DSPS: 27612427; Offset : -4323503585
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{d5444b8 type 2 when 843817 android} when 843817
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2932f5f6 type 0 when 1449757443240 com.android.vending} when 1449757443240
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 26195(1154KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 2.211ms total 87.358ms
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 858357260927; DSPS: 28267832; Offset : -4323505008
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7868): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 878359068210; DSPS: 28923251; Offset : -4323498940
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{22973201 type 0 when 1449757467632 com.android.vending} when 1449757467632
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7868): [1] 5.onFinished: Scheduling replication attempt 3.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 898361950910; DSPS: 29578705; Offset : -4323484917
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{32107f18 type 0 when 1449757492633 com.android.vending} when 1449757492633
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7868): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 918363866998; DSPS: 30234128; Offset : -4323491386
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{102470eb type 0 when 1449757516502 com.android.vending} when 1449757516502
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7868): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 938365458969; DSPS: 30889540; Offset : -4323486407
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2e30a3d5 type 2 when 943249 com.android.bluetooth} when 943249
,W/bt-smp  ( 3762): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3762): Plain text(LSB ~ MSB) = 24 aa 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3762): Encrypted text(LSB ~ MSB) = fa e7 a5 8a 12 9b bd 46 80 8f ab ff 72 8f b8 fe 
W/bt-btm  ( 3762): Stopping oneshot timer
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1f276adb type 0 when 1449757537441 com.android.vending} when 1449757537441
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7868): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 958367454066; DSPS: 31544966; Offset : -4323505366
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 978369310829; DSPS: 32200386; Offset : -4323479709
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,D/WifiController( 1038): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3762): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4264): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 998372045717; DSPS: 32855836; Offset : -4323491299
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1018373883679; DSPS: 33511256; Offset : -4323484444
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1038376117941; DSPS: 34166689; Offset : -4323477991
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1058377928610; DSPS: 34822109; Offset : -4323498428
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1078380687145; DSPS: 35477559; Offset : -4323486475
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/LIA_Informant_Tips_UserGuideCardScheduler( 3704): onReceive! : com.lge.ia.task.informant.dyk.userguide.UserGuideCardScheduler
I/LIA_Informant_Tips_LogTracer( 3704): [Log Tracer - Schedule Transition] UserGuide, ALARM_RECEIVE : 2015-12-10 15:27:53...... Request
D/LIA_Informant_Tips_CardFlowHandlerBase( 3704): onSchedule() - Intent { act=com.lge.ia.task.informant.dyk.userguide.UserGuideCardScheduler flg=0x14 (has extras) }
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1a232c45 type 0 when 1449757560762 com.lge.ia.task.informant} when 1449757560762
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,I/LIA_Informant_BoardStateUtil( 3704): isEnabledGBoard() : count > 0 - true
D/LIA_Informant_BoardStateUtil( 3704): isEnabledMyGuideOfGboard : true
,D/LIA_Informant_Tips_CardFlowHandlerBase( 3704): onSchedule() : Board Status : Show Card - 7
I/LIA_Informant_Tips_CardFlowHandlerBase( 3704): onSchedule() : cardType - guide
D/LIA_Informant_Tips_FeatureConditionChecker( 3704): check (maxCardNum : 1)
D/LIA_Informant_Tips_UserGuideDBManager( 3704): getCandidateFeatureList
D/LIA_Informant_Tips_UserGuideXMLParser( 3704): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
,I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step A : featureList size - 10
D/LIA_Informant_Tips_UserGuideDBManager( 3704): getTotalUsed
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 7, featureName - ugc_qremote_on_alarm, appName - qremote, appUsed - 0, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 22, featureName - ugc_oho_dial_keypad, appName - one_hand_operation, appUsed - 0, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 3, featureName - ugc_camera_dual, appName - camera, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 9, featureName - ugc_qremote_always_home, appName - qremote, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 12, featureName - ugc_battery_power_saver, appName - battery, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 16, featureName - ugc_gesture_motion_call, appName - gesture, appUsed - 8, score - 4.000335462594356
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 23, featureName - ugc_oho_lockscreen, appName - one_hand_operation, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 26, featureName - ugc_lg_backup, appName - lg_backup, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 28, featureName - ugc_home_edit_page, appName - home, appUsed - 0, score - 4.999999900000005
,I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step B : featureID - 31, featureName - ugc_home_folder, appName - home, appUsed - 0, score - 4.999999900000005
D/LIA_Informant_Tips_UserGuideDBManager( 3704): getAppListOfPrevCard
D/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : prevAppList - navigationbar
D/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : featureList size - 10
D/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : prevAppList - navigationbar
,D/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : all same app : false
D/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : featureList isAllContains prevApp : false
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : getFeatureOfMinScore feature - ugc_qremote_on_alarm, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 3704): Step C : selectLowestScoreCardList - cardList size=1
D/LIA_Informant_Tips_CardFlowHandlerBase( 3704): getCardGeneratorList() : boardStatus - 7
D/LIA_Informant_Tips_UserGuideXMLParser( 3704): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
,D/LIA_Informant_Tips_UserGuideXMLParser( 3704): getParamList() : paramList-1
I/LIA_Informant_Tips_CardFormUtil( 3704): getDYKCardPath() : cardType - guide, path - file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html
I/LIA_Informant_Tips_LogTracer( 3704): [Log Tracer - Card Generation] UserGuide, DYK, CARD_CMD_ADD, guide_1111111111116_ugc_qremote_on_alarm...... Request
D/LIA_Informant_Tips_DYKCardGenerator( 3704): sendCard : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html?id=guide_1111111111116_ugc_qremote_on_alarm&title=[@string/sp_quicksettings_remote_control_NORMAL]&desc=[@string/dyk_ugc_qremote_on_alarm_desc]&bgimg=res/drawable/q_remote.jpg&iconimg=res/drawable/ic_null.png&goto_app=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.lge.qremote%2F.settings.help.HelpActivity%3BS.help_name%3DWidgetOnNotification%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend&url=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.lge.qremote%2F.settings.help.HelpActivity%3BS.help_name%3DWidgetOnNotification%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend
D/LIA_Informant_ActionManagerMessageHandler( 3704): setCard
,D/ActionManagerService( 1908): executeCardCommand(0, com.lge.intent.category.doyouknow.GUIDE)
D/LIA_Informant_Tips_UserGuideDBManager( 3704): setUploadCardInfo
I/LIA_Informant_Tips_LogTracer( 3704): [Log Tracer - Card Generation] UserGuide, GBoard, CARD_CMD_ADD, guide_1111111111116_1449757673225...... Request
,I/LIA_Informant_Tips_CardFormUtil( 3704): getGBoardCardPath() : cardType - guide, path - file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html
D/LIA_Informant_Tips_GBoardCardGenerator( 3704): sendCard : file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LIA_Informant_ActionManagerMessageHandler( 3704): setCard
D/ActionManagerService( 1908): executeCardCommand(0, com.lge.intent.category.gboard.DOYOUKNOW)
D/LIA_Informant_Tips_UserGuideDBManager( 3704): setUploadCardInfo
I/LIA_Informant_Tips_LogTracer( 3704): [Log Tracer - Card Generation] UserGuide, Concierge, CARD_CMD_ADD, guide_1111111111116...... Request
,D/LIA_Informant_Tips_ConciergeCardGenerator( 3704): sendCard : my_guide?id=guide_1111111111116&summary=%5B%40string%2Fguide_summary%5D&source=%5B%40string%2Fguide_source%5D&key_data=id&category=com.lge.intent.category.doyouknow.*&expire_time=1449930473246
D/LIA_Informant_ActionManagerMessageHandler( 3704): setCard
D/ActionManagerService( 1908): executeCardCommand(0, com.lge.intent.category.CONCIERGE)
D/LIA_Informant_Tips_UserGuideDBManager( 3704): setUploadCardInfo
D/[Concierge]Service( 2579): Card command received
V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/concierge) projection([id]) order(null)
I/LIA_Informant_Tips_UserGuideCardFlowHandler( 3704): updateStateCardGenerated() : UserGuide Working Duration Count is reset to 1
,D/[Concierge]CardInfo( 2579): CardInfo loaded.  Path (/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide), Version (1.0.0)
D/[Concierge]CardNotifier( 2579): Send card notification. Card id : guide_1111111111116
,D/LIA_Informant_Tips_UserGuideCardScheduler( 3704): cancel
I/LIA_Informant_Tips_LogTracer( 3704): [Log Tracer - Schedule Transition] UserGuide, DATE_RESET : working count : 1...... Request
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
I/ActivityManager( 1038): Start proc com.lge.doyouknow for broadcast com.lge.doyouknow/.DYKBoardReceiver: pid=8133 uid=10036 gids={50036, 9997, 3003, 1028} abi=armeabi
,D/LIA_MrGDBLogger_BoardDetector( 3704): [dreamwood]dreamwood check json : {"card_cmd":"add","card_name":"my_guide","day_of_week":5,"id":"[guide_1111111111116]"}
,I/DYKBoardReceiver( 8133): action = com.lge.mrg.service.action.CARD_COMMAND
,I/DYKBoardReceiver( 8133): Card info : card Command = 0 category = com.lge.intent.category.doyouknow.GUIDE uri =file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html?id=guide_1111111111116_ugc_qremote_on_alarm&title=[@string/sp_quicksettings_remote_control_NORMAL]&desc=[@string/dyk_ugc_qremote_on_alarm_desc]&bgimg=res/drawable/q_remote.jpg&iconimg=res/drawable/ic_null.png&goto_app=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.lge.qremote%2F.settings.help.HelpActivity%3BS.help_name%3DWidgetOnNotification%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend&url=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.lge.qremote%2F.settings.help.HelpActivity%3BS.help_name%3DWidgetOnNotification%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend
D/DYKBoardProvider( 8133): insert
V/BoardContentProvider( 3704): insert(): uri(content://com.lge.mrg.boardcontent/doyouknow)
,I/BoardContentProvider( 3704): notify insert: uri = content://com.lge.mrg.boardcontent/doyouknow
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.lge.concierge id=915 notification=Notification(pri=0 contentView=null vibrate=[0,0,0,0] sound=content://media/internal/audio/media/39 defaults=0x0 flags=0x11 color=0x00000000 vis=PUBLIC)
D/DYKBoard:MainActivity( 8133): loadingFullCard
D/ZenLog  ( 1038): intercepted: 0|com.lge.concierge|915|null|10017,none
V/NotificationService( 1038): pkg=com.lge.concierge canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.lge.concierge|915|null|10017
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.lge.concierge|915|null|10017, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=[0,0,0,0] sound=content://media/internal/audio/media/39 defaults=0x0 flags=0x11 color=0x00000000 vis=PUBLIC)
D/lightsbindercall( 1038): calling ... updateLightList
E/lightsbindercall( 1038): virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction Start!!
D/BoardContract.Concierge( 2579): insert
,V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/concierge) projection([id]) order(null)
D/LEDService( 1955): updateLightListInternal() : action=2 pkg=com.lge.concierge
E/lightsbindercall( 1038): virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction End!! (error code 0)
V/BoardContentProvider( 3704): insert(): uri(content://com.lge.mrg.boardcontent/concierge)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): post do add job
D/LgeQuickCoverNotificationData( 1403): add : 3
D/LgeQuickCoverNotificationData( 1403): do add job
D/LgeQuickCoverNotificationData( 1403): showAll4
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
I/BoardContentProvider( 3704): notify insert: uri = content://com.lge.mrg.boardcontent/concierge
D/[Concierge]AConciergeServiceListener( 2073): Msg received + type = 0
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/[Concierge][WearableNotifier]( 2579): sendWearableNotification, Name = my_guide, title = Smart Tips
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=4
D/[Concierge]CardInfo( 2073): CardInfo loaded.  Path (/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide), Version (1.0.0)
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/[Concierge]StringReplacer( 2073): Token not found. Keep token string : param/id
W/[Concierge]StringReplacer( 2073): Token not found. Keep token string : param/id
W/[Concierge]StringReplacer( 2073): Token not found. Keep token string : encode.json:card/action_delete
D/[Concierge]WebView( 2073): Add card 
,I/PeerNotificationManager( 2579): startService :: notifyToSideOnly
I/PeerNotificationManager( 2579): SideServiceConnection
W/ActivityManager( 1038): Unable to start service Intent { act=com.lge.wmanClients.notification.SideNotificationService pkg=com.lge.wman } U=0: not found
D/[Concierge][WearableNotifier]( 2579): sendWearableNotification, sent id = 1195088426
,D/[Concierge]WebView_Console( 2073): Theme name is empty or null. For : DIV. Apply default theme
D/[Concierge]WebView_Console( 2073): converting : /system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxhdpi/style.css
,D/[Concierge]WebView_Console( 2073): converting : /system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxxhdpi/style.css
,I/WebViewFactory( 8133): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/[Concierge]WebView( 2073): Is VZW : false
,I/LibraryLoader( 8133): Loading: webviewchromium
I/LibraryLoader( 8133): Time to load native libraries: 3 ms (timestamps 4293-4296)
I/LibraryLoader( 8133): Expected native library version number "",actual native library version number ""
D/[Concierge]WebView( 2073): Is VZW : false
,D/[Concierge]WebView( 2073): isEulaAccepted : true
V/WebViewChromiumFactoryProvider( 8133): Binding Chromium to main looper Looper (main, tid 1) {1360b94a}
,I/LibraryLoader( 8133): Expected native library version number "",actual native library version number ""
I/chromium( 8133): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8133): Initializing chromium process, renderers=0
W/art     ( 8133): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  320): registerClient() client 0xb1019c40, uid 10036
W/AudioManagerAndroid( 8133): Requires BLUETOOTH permission
,W/chromium( 8133): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8133): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
I/chromium( 8133): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
D/[Concierge]WebView_Console( 2073): url("concierge_popup_icon_17.png") -> url(/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxhdpi/concierge_popup_icon_17.png)
I/Adreno-EGL( 8133): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8133): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8133): Build Date: 12/12/14 금
I/Adreno-EGL( 8133): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8133): Remote Branch: 
I/Adreno-EGL( 8133): Local Patches: 
I/Adreno-EGL( 8133): Reconstruct Branch: 
D/[Concierge]WebView_Console( 2073): url("concierge_popup_icon_17.png") -> url(/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxxhdpi/concierge_popup_icon_17.png)
,W/chromium( 8133): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 8133): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 8133): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 8133): onDetachedFromWindow called when already detached. Ignoring
W/art     ( 8133): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 8133): Attempt to remove local handle scope entry from IRT, ignoring
,D/DYKBoard:MainActivity( 8133): mDYKEventWebView load contents
I/ActivityManager( 1038): Killing 7372:com.lge.email/u0a23 (adj 15): empty #17
D/LgDataFeature( 8133): LgDataFeature() Constructor: none
D/LgDataFeature( 8133): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_7372/cgroup.procs: No such file or directory
,D/GBoardUriUtils( 2073): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,D/GBoardWebViewUtils( 2073): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardCardProvider( 2073): deleteById id:new_feature_1111111111111_1449660465987
V/BoardContentProvider( 3704): delete(): uri(content://com.lge.mrg.boardcontent/gboard)
,I/BoardContentProvider( 3704): notify delete: uri = content://com.lge.mrg.boardcontent/gboard
W/System.err( 2073): java.lang.NumberFormatException: Invalid int: "null"
W/System.err( 2073): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 2073): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 2073): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 2073): 	at com.lge.launcher2.gboard.database.GBoardCardProvider.getExpireTime(GBoardCardProvider.java:47)
W/System.err( 2073): 	at com.lge.launcher2.gboard.database.GBoardCardProvider.insertCard(GBoardCardProvider.java:34)
W/System.err( 2073): 	at com.lge.launcher2.gboard.GBoardWebViewUtils.addCard(GBoardWebViewUtils.java:44)
,W/System.err( 2073): 	at com.lge.launcher2.gboard.GBoardReceiver.onReceive(GBoardReceiver.java:36)
W/System.err( 2073): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
W/System.err( 2073): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
W/System.err( 2073): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
W/System.err( 2073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2073): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2073): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 2073): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2073): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2073): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 2073): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/GBoardCardProvider( 2073): insert
V/BoardContentProvider( 3704): insert(): uri(content://com.lge.mrg.boardcontent/gboard)
I/BoardContentProvider( 3704): notify insert: uri = content://com.lge.mrg.boardcontent/gboard
,I/chromium( 8133): [INFO:CONSOLE(1)] "Uncaught ReferenceError: collapseCard is not defined", source:  (1)
,I/GBoardtInterface( 2073): exportHTML()
,I/chromium( 8133): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 8133): 
,I/chromium( 8133): [INFO:CONSOLE(738)] "on load event", source: file:///android_asset/www/js/controlCards.js (738)
,E/DYKBoard( 8133): onPageFinished url:file:///android_asset/www/dykContainer.html?deviceHeight=531
V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(null)
V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(null)
V/BoardContentProvider( 3704): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(create_time asc)
,D/DYKBoard:MainActivity( 8133): mDYKEventWebView load contents
,I/chromium( 8133): [INFO:CONSOLE(61)] "addAllCard-----------------------", source: file:///android_asset/www/js/controlCards.js (61)
,I/chromium( 8133): [INFO:CONSOLE(50)] "[object Object]", source: file:///android_asset/www/libs/form_converter.js (50)
,I/chromium( 8133): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 8133): 
,I/chromium( 8133): [INFO:CONSOLE(50)] "[object Object]", source: file:///android_asset/www/libs/form_converter.js (50)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 8133): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_textlink_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/drawable/dyk_textlink_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_oiscamera_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/drawable/dyk_oiscamera_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/ic_setting.png') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/drawable/ic_setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_guestmode_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/drawable/dyk_guestmode_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/ic_launcher_camera.png') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_dualwindow_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/drawable/dyk_dualwindow_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartkeyboard_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/drawable/dyk_smartkeyboard_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quadhd_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/drawable/dyk_quadhd_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartbulletin_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/drawable/dyk_smartbulletin_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quickcircle_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/drawable/dyk_quickcircle_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quadhd_bg.jpg') -> url(file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/drawable/dyk_quadhd_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quickcircle_bg.jpg') -> url(file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/drawable/dyk_quickcircle_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartbulletin_bg.jpg') -> url(file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/drawable/dyk_smartbulletin_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quickcirclecase_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/drawable/dyk_quickcirclecase_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartkeyboard_bg.jpg') -> url(file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/drawable/dyk_smartkeyboard_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url('res/drawable/dyk_dualwindow_bg.jpg') -> url(file:///data/data/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/drawable/dyk_dualwindow_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_move_cursor.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_move_cursor.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/camera_switch.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_switch.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/dual_window.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/dual_window.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/camera_voice_shutter.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_voice_shutter.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_suggestion.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_suggestion.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/camera_gestureshot.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_gestureshot.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/gesture_call.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/gesture_call.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/home_cleanview.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/home_cleanview.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_split.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_split.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/internet.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/internet.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_internet.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_internet.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_path_input.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_path_input.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/camera_magic_focus.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_magic_focus.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_onehand.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_onehand.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/gesture_call.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/gesture_call.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/home_iconchange.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/home_iconchange.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/navigation.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/navigation.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/q_remote.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/q_remote.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/camera_panorama.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_panorama.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 8133): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 8133): [INFO:CONSOLE(95)] "attachInitialCard-----------------------", source: file:///android_asset/www/js/controlCards.js (95)
I/chromium( 8133): [INFO:CONSOLE(176)] "attach remaining card -------------", source: file:///android_asset/www/js/controlCards.js (176)
,I/chromium( 8133): [INFO:CONSOLE(180)] "calculate rotation degree-------------------", source: file:///android_asset/www/js/animation.js (180)
,I/chromium( 8133): [INFO:CONSOLE(111)] "accordion collapse effect ----------------------------- ", source: file:///android_asset/www/js/animation.js (111)
,I/chromium( 8133): [INFO:CONSOLE(602)] "exportDYKHTML----------------", source: file:///android_asset/www/js/controlCards.js (602)
,D/DYKBoard( 8133): exportDYKHTML(), GBoard refresh = 1
,D/DYKBoard( 8133): Out File Path =/data/data/com.lge.doyouknow/files/www/dykContainer.html
W/ScreenOrientationListener( 8133): Removing an inexistent observer!
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1098382027346; DSPS: 36132963; Offset : -4323488919
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll4
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=4
,D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7868): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7868): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7868): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7868): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7868): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7868): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7868): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 7868): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = ipv4.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = ipv4.google.com succeed
,E/PlayEventLogger( 7868): Status 503 without retry-after header
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1118384053849; DSPS: 36788389; Offset : -4323476471
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1138386231028; DSPS: 37443821; Offset : -4323496663
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1158388545812; DSPS: 38099257; Offset : -4323501057
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1178390561951; DSPS: 38754683; Offset : -4323499209
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{ecc5a23 type 2 when 1188705 com.google.android.gms} when 1188705
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/GCM     ( 2118): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1198392713922; DSPS: 39410113; Offset : -4323483520
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7694): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7694): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1e31aeb5
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1218394574123; DSPS: 40065534; Offset : -4323484996
,I/UsageStatsService( 1038): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1238396753646; DSPS: 40720966; Offset : -4323502634
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1258398793743; DSPS: 41376392; Offset : -4323476749
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1278401543007; DSPS: 42031843; Offset : -4323504455
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1298403450030; DSPS: 42687265; Offset : -4323489679
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2a8b3b20 type 2 when 1304522 android} when 1304522
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,I/BooksSync( 6944): Starting books sync
,D/BooksSync( 6944): started syncMyEbooks
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 27513(1244KB) AllocSpace objects, 6(224KB) LOS objects, 33% free, 44MB/66MB, paused 3.423ms total 155.771ms
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll4
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=4
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7228680633760788755&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll4
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=4
W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
,W/ApiaryClient( 6944): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7228680633760788755&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2118): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2118): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2118): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2118): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2118): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll4
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=4
,W/GLSActivity( 2118): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2118): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2118): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2118): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2118): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6944): Authentication error
E/BooksAccountManager( 6944): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6944): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6944): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6944): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6944): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{369f9f80 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6944): Error response from books API: {
W/ApiaryClient( 6944):  "error": {
W/ApiaryClient( 6944):   "errors": [
W/ApiaryClient( 6944):    {
W/ApiaryClient( 6944):     "domain": "global",
W/ApiaryClient( 6944):     "reason": "required",
W/ApiaryClient( 6944):     "message": "Login Required",
W/ApiaryClient( 6944):     "locationType": "header",
W/ApiaryClient( 6944):     "location": "Authorization"
W/ApiaryClient( 6944):    }
W/ApiaryClient( 6944):   ],
W/ApiaryClient( 6944):   "code": 401,
W/ApiaryClient( 6944):   "message": "Login Required"
W/ApiaryClient( 6944):  }
W/ApiaryClient( 6944): }
W/ApiaryClient( 6944): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7228680633760788755&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6944): Headers:
W/ApiaryClient( 6944): accept-encoding: [gzip]
W/ApiaryClient( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6944): gdata-version: 2
,E/BooksSync( 6944): Soft error: 
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7228680633760788755&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
,E/BooksSync( 6944): Sync error
E/BooksSync( 6944): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6944): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7228680633760788755&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6944): Headers:
E/BooksSync( 6944): accept-encoding: [gzip]
E/BooksSync( 6944): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6944): gdata-version: 2
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6944): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6944): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6944): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6944): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6944): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6944): {
E/BooksSync( 6944):  "error": {
E/BooksSync( 6944):   "errors": [
E/BooksSync( 6944):    {
E/BooksSync( 6944):     "domain": "global",
E/BooksSync( 6944):     "reason": "required",
E/BooksSync( 6944):     "message": "Login Required",
E/BooksSync( 6944):     "locationType": "header",
E/BooksSync( 6944):     "location": "Authorization"
E/BooksSync( 6944):    }
E/BooksSync( 6944):   ],
E/BooksSync( 6944):   "code": 401,
E/BooksSync( 6944):   "message": "Login Required"
E/BooksSync( 6944):  }
E/BooksSync( 6944): }
E/BooksSync( 6944): 
E/BooksSync( 6944): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6944): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6944): 	... 8 more
I/BooksSync( 6944): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1304522, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1318405655803; DSPS: 43342697; Offset : -4323481014
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{4854cd6 type 2 when 1334863 android} when 1334863
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1338407583452; DSPS: 43998121; Offset : -4323506568
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1358409759538; DSPS: 44653552; Offset : -4323497283
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1378411914478; DSPS: 45308982; Offset : -4323478573
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1398414123013; DSPS: 45964415; Offset : -4323497848
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1418415985140; DSPS: 46619836; Offset : -4323497266
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1438417964872; DSPS: 47275261; Offset : -4323501126
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1458420754032; DSPS: 47930712; Offset : -4323489169
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1478422625899; DSPS: 48586133; Offset : -4323478822
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1498424223391; DSPS: 49241546; Offset : -4323498683
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1518426046144; DSPS: 49896965; Offset : -4323476597
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1538428099573; DSPS: 50552393; Offset : -4323498104
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1558429883316; DSPS: 51207811; Offset : -4323484589
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1578431861121; DSPS: 51863236; Offset : -4323490427
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1598433446009; DSPS: 52518648; Offset : -4323492478
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1618435032929; DSPS: 53174060; Offset : -4323492395
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1638437069118; DSPS: 53829487; Offset : -4323500935
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1658439181455; DSPS: 54484916; Offset : -4323494233
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1678441701968; DSPS: 55140358; Offset : -4323476291
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1698443936335; DSPS: 55795792; Offset : -4323500070
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1718446718724; DSPS: 56451243; Offset : -4323494779
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1738448656007; DSPS: 57106666; Offset : -4323480000
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{daf1b57 type 2 when 1749739 android} when 1749739
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1758450734438; DSPS: 57762094; Offset : -4323476920
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1778452599170; DSPS: 58417515; Offset : -4323473838
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1798454474839; DSPS: 59072937; Offset : -4323490129
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1818456467226; DSPS: 59728362; Offset : -4323481542
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1838458583365; DSPS: 60383792; Offset : -4323501554
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=456203640, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{22ea32d type 2 when 1843269 com.android.bluetooth} when 1843269
,W/bt-smp  ( 3762): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3762): Plain text(LSB ~ MSB) = 93 87 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3762): Encrypted text(LSB ~ MSB) = c3 cd 2d 73 30 48 8b 5d c8 cf 1e a2 5a 07 95 37 
W/bt-btm  ( 3762): Stopping oneshot timer
I/ProcessStatsService( 1038): Prepared write state in 9ms
,I/ProcessStatsService( 1038): Prepared write state in 28ms
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=456203640 [*alarm*], flags=0x0
,I/ProcessStatsService( 1038): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-52-39.bin
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1858460593670; DSPS: 61039217; Offset : -4323474892
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1878462752674; DSPS: 61694648; Offset : -4323482533
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1898464318186; DSPS: 62350059; Offset : -4323473572
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1918466331512; DSPS: 63005486; Offset : -4323504950
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1938468656192; DSPS: 63660922; Offset : -4323499606
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1958470570507; DSPS: 64316344; Offset : -4323477277
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1978472711541; DSPS: 64971775; Offset : -4323503017
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1998474783044; DSPS: 65627203; Offset : -4323506736
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2018476858192; DSPS: 66282630; Offset : -4323476317
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2038478954279; DSPS: 66938059; Offset : -4323485891
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2058481487969; DSPS: 67593502; Offset : -4323485082
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2078483618065; DSPS: 68248932; Offset : -4323491268
,TIME-OUT KILL (timeout was 1800000ms)
```
