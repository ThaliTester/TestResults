#### Test 5615109370bee58_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 277305058680; DSPS: 9228157; Offset : -4331459401
,D/AndroidRuntime( 7167): 
D/AndroidRuntime( 7167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7167): CheckJNI is OFF
D/AndroidRuntime( 7167): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1935): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{3233070b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{3233070b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7187 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7167): Shutting down VM
V/ActivityManager( 1035): Display changed displayId=0
D/DSDPConnection( 1846): Display #0 changed.
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{22db334 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{2847555d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7187): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7187): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7187): Loading: webviewchromium
I/LibraryLoader( 7187): Time to load native libraries: 4 ms (timestamps 5585-5589)
,I/LibraryLoader( 7187): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7187): Binding Chromium to main looper Looper (main, tid 1) {198b2fe4}
I/LibraryLoader( 7187): Expected native library version number "",actual native library version number ""
I/chromium( 7187): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7187): Initializing chromium process, renderers=0
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  312): registerClient() client 0xb14fd780, uid 10311
,W/chromium( 7187): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7187): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7187): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b99b33d:true
I/Adreno-EGL( 7187): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7187): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7187): Build Date: 12/12/14 금
I/Adreno-EGL( 7187): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7187): Remote Branch: 
I/Adreno-EGL( 7187): Local Patches: 
I/Adreno-EGL( 7187): Reconstruct Branch: 
,W/chromium( 7187): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7187): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7187): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7187): CordovaWebView is running on device made by: LGE
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7187): Render dirty regions requested: true
I/OpenGLRenderer( 7187): Initialized EGL, version 1.4
D/OpenGLRenderer( 7187): Enabling debug mode 0
D/Atlas   ( 7187): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{16a4ccf u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7187): LgDataFeature() Constructor: none
D/LgDataFeature( 7187): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e14e516,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +585ms (total +661ms)
I/Timeline( 7187): Timeline: Activity_idle id: android.os.BinderProxy@1f0c5a14 time:285987
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{296189e8 u0 com.test.thalitest/.MainActivity t4} time:285989
D/JsMessageQueue( 7187): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7187): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435085056
D/JX-Cordova( 7187): jxcore cordova android initializing
E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7187): Initializing JXcore engine
W/jxcore-log( 7187): JXcore engine is ready
,W/jxcore-log( 7187): Starting JXcore engine
W/.test.thalitest( 7187): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7463]" dev="sockfs" ino=7463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7187): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 7187): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10487]" dev="sockfs" ino=10487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7187): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7187): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[35111]" dev="sockfs" ino=35111 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7187): Platform android
W/jxcore-log( 7187): 
W/jxcore-log( 7187): Process ARCH arm
W/jxcore-log( 7187): 
,I/art     ( 7187): Background sticky concurrent mark sweep GC freed 133139(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.830ms total 125.058ms
I/jxcore-log( 7187): JXcore Cordova bridge is ready!
I/jxcore-log( 7187): 
W/jxcore-log( 7187): JXcore engine is started
,I/jxcore-log( 7187): Toggling radios to true
I/jxcore-log( 7187): 
,D/BluetoothAdapter( 7187): enable(): BT is already enabled..!
D/WifiService( 1035): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=7187, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: true pid=7187, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1035): disconnect pid=7187, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1035): [288,918,827 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1035): reconnect pid=7187, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7187): Radios toggled
I/jxcore-log( 7187): 
I/jxcore-log( 7187): My device name is: LGE-LG-D855
I/jxcore-log( 7187): 
,I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1035): InitialState.processMessage what=4
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1035): DISCONNECT: returned true
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
,D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1035): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7257 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2067): Read error: ssl=0xaf4d6200: I/O error during system call, Connection timed out
E/WifiStateMachine( 1035): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1035):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 1035): [289,037,632 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): ignoring duplicate network state non-change
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 0
,D/WifiNative-wlan0( 1035): RECONNECT: returned true
E/WifiStateMachine( 1035):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289059
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289059
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
V/NativeCrypto( 2067): SSL shutdown failed: ssl=0xaf4d6200: I/O error during system call, Broken pipe
D/WifiHS20( 1035): hidePasspointNotification off =false
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on <unknown ssid>
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  308): Clearing all IP addresses on wlan0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289112  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289112  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289117  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1035): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289123  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateSCANNING
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1035): Removing idletimer
D/TelephonyNetworkFactory-1( 1846): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: f,alse, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
,W/ResourcesManager( 7257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7257): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-171ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7257): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7257): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7257): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6176:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6176/cgroup.procs: No such file or directory
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7257): LgDataFeature() Constructor: none
D/LgDataFeature( 7257): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
,D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1035): Killing 6203:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_6203/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2641): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=291109  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=291118  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2641): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=33 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=291206  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=291207  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291208
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291208
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291208
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291209
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291209
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=291209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=291213  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2641): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=291215  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=291215  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=36 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provid,er.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7257): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=291219
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=291219
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1035): doString: [STATUS]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 7257): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7257): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7257): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7257): [AUTORUN] setTetherStatus() : status=false
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1035): Got NetworkAgent Messenger
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
,E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine( 1035): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1035): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=291269  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=291269  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=291270  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=291271  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=291271  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=291272  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@309a69a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@309a69a6 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1035): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1035): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1035): Adding iface wlan0 to network 101
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  308): netlink response contains error (File exists)
D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1035): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/TelephonyNetworkFactory-1( 1846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
W/dsqn    ( 7340): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7340): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/DSQN    ( 7340): DSQN ssw
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6988): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6988): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6988): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7257): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7257): MCCMNC not supported: null
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6988): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6988): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6988): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  308): argv[0]=dsqncommand
,D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1035): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 14:19:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453126794468], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453126794441]}
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
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7346): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7346): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/dhcpcd  ( 7346): version 5.5.6 starting
E/dhcpcd  ( 7346): get_duid: m
D/dhcpcd  ( 7346): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7346): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7187): 
,D/dhcpcd  ( 7346): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7346): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7346): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7346): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7346): wlan0: sending REQUEST (xid 0x8dab4b72), next in 3.58 seconds
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6672): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{11176b6 type 2 when 292153 com.google.android.gms} when 292153
I/NetworkMonitor( 5609): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6672): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5609): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7187): 
I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7381 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  351): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 10.615ms
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7187): 
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.038ms
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 8.949ms
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7187): 
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7187): 
I/AppUp4:AppBoxCP( 7381): onCreate
W/AppUp4:DB( 7381):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7381):  setFingerPrint start
I/AppUp4:DB( 7381):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7381):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7381):  SDK version = 21
I/AppUp4:DB( 7381):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7381): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7381): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7381): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7381): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7381): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7381): onReceive
D/LgDataFeature( 7381): LgDataFeature() Constructor: none
D/LgDataFeature( 7381): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7381): Context : android.app.ReceiverRestrictedContext@1f09e302
D/AppUp4:CustFacade( 7381): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7381): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7381): begin check event
I/AppUp4:CustModeStarterReceiver( 7381): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7381): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7381): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7381): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7381): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1035): Killing 6601:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10004/pid_6601/cgroup.procs: No such file or directory
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3363): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3363): DownloadService onCreate
I/DownloadManager( 3363): in removeSpuriousFiles
V/DownloadManager( 3363): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3363): created cursor android.database.sqlite.SQLiteCursor@36ee261 on behalf of 3363
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3363): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3363): DownloadService onStartCommand
V/DownloadManager( 3363): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3363): in trimDatabase
V/DownloadManager( 3363): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3363): created cursor android.database.sqlite.SQLiteCursor@c067274 on behalf of 3363
V/DownloadManager( 3363): created cursor android.database.sqlite.SQLiteCursor@f56439d on behalf of 3363
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3363): processing inserted download 1
,V/DownloadManager( 3363): processing inserted download 4
V/DownloadManager( 3363): processing inserted download 7
V/DownloadManager( 3363): processing inserted download 8
V/DownloadManager( 3363): processing inserted download 9
V/DownloadManager( 3363): processing inserted download 10
V/DownloadManager( 3363): processing inserted download 16
V/DownloadManager( 3363): processing inserted download 17
V/DownloadManager( 3363): processing inserted download 18
V/DownloadManager( 3363): processing inserted download 21
V/DownloadManager( 3363): processing inserted download 22
V/DownloadManager( 3363): DownloadService onDestroy
D/eas_req ( 6724): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/jxcore-log( 7187): Test app app.js loaded
I/jxcore-log( 7187): 
,I/chromium( 7187): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7187): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7187): 
I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7411 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6724): JNI_OnLoad()
I/HubEmail( 6724): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNatives()
I/HubEmail( 6724): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNativeMethods()
I/HubEmail( 6724): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6724): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/chromium( 7187): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dhcpcd  ( 7346): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7346): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7346): wlan0: adding IP address 192.168.1.141/24
E/WifiStateMachine( 1035):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/dhcpcd  ( 7346): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7346): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7346): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/dhcpcd  ( 7346): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7346): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7346): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1035): identical MTU - not setting
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = false
,I/ActivityManager( 1035): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7448 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 7187): --= Surplus to requirements =--
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): ****TEST TOOK:  ms ****
I/jxcore-log( 7187): 
I/jxcore-log( 7187): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7187): 
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/chromium( 7187): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7187): 
,D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
V/FormManager( 7411): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7411): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7490 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6751:com.android.gallery3d/u0a27 (adj 15): empty #17
D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1035): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
D/AndroidRuntime( 7484): 
D/AndroidRuntime( 7484): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7484): CheckJNI is OFF
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_6751/cgroup.procs: No such file or directory
,I/ActivityManager( 1035): Killing 6805:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/AndroidRuntime( 7484): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6805/cgroup.procs: No such file or directory
,W/PackageSettings( 1035): Skipping PackageSetting{11dd586b com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7521 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6850:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1035): Killing 7187:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1035): WIN DEATH: Window{16a4ccf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1035): Client connection lost with reason: 4
,D/InputDispatcher( 1035): Window went away: Window{16a4ccf u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1035):   Force finishing activity ActivityRecord{296189e8 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
,I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1035):   Force finishing activity ActivityRecord{296189e8 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1035): Duplicate finish request for ActivityRecord{296189e8 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{54fded2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{1520ba3 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2027): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2027): [Launcher.java:903:onResume()]onResume
W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_6850/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2027): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
W/ActivityManager( 1035): Spurious death for ProcessRecord{118aadc1 7187:com.test.thalitest/u0a311}, curProc for 7187: null
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
,E/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3769): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1810): Ignoring removeGeofence because network location is disabled.
,D/LIA_Service_RemotePackageHandler( 1989): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/art     ( 4613): Explicit concurrent mark sweep GC freed 15077(878KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 435us total 91.927ms
,I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,W/System.err( 4560): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4560): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4560): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4560): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4560): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4560): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4560): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4560): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4560): 	at java.lang.reflect.Method.invoke(Native Method)
D/ActionManagerService( 1900): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3769): handleMessage: what(1000) actionID(0x1000003)
W/System.err( 4560): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4560): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4560): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7545 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7521): Almond Protected OAT
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2027): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1035):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/[LGHome]EVENT( 2027): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2027): [Launcher.java:1114:onPause()]onPause
I/art     ( 1035): Explicit concurrent mark sweep GC freed 80499(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 2.283ms total 216.731ms
I/art     ( 1035): WaitForGcToComplete blocked for 13.804ms for cause Explicit
D/ActionManagerService( 1900): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 3769): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3769): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2027): , create_time: 1430558575574
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
,I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2027): , create_time: 1430558575600
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2027): , create_time: 1452774039338
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/LockScreenSettings( 7545): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e14e516,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ActivityManager( 1035): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3839): [BTUI] [-] updateMediaPlayerInfo
D/WeatherApplication( 7521): removeAccount
D/WallpaperManager( 2027): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/WeatherApplication( 7521): Account.length = 0
E/WeatherApplication( 7521): OPERATOR:OPEN
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
D/WeatherAncestor( 7521): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:19:57
,I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1863): split_name #11 / not available #0
D/SplitUIService( 1863): removed split : 
D/Weather.Utils( 7521): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7521): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7521): 2 : This is isUpdating : false
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/administrator( 1035): Handling package changes for user 0
D/WeatherAncestor( 7521): connectivity changed - connection : true
,W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
,D/WeatherService( 7521): 2 : isServiceAlived():false forecastCache:null
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
D/SplitUIManager( 1863): split_name #11 / not available #0
I/SplitUIService( 1863): split app #11
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
,I/ActivityManager( 1035): Killing 6917:com.lge.eula/1000 (adj 15): empty #17
D/ForecastDataCache( 7521): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7521): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7521): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7521): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7521): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:19:57
,I/NotificationService( 1035): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1035): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 1035): Explicit concurrent mark sweep GC freed 11629(642KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.416ms total 181.159ms
,D/KeyguardModel( 1472): handleShortcutListChanged...
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6917/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2027): [Launcher.java:5349:onStop()]onStop
I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7568 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1035): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/ActivityManager( 1035): Killing 6879:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AndroidRuntime( 7484): Shutting down VM
,V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2027): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/KeyguardModel( 1472): handleShortcutListChanged...
,W/libprocessgroup( 1035): failed to open /acct/uid_10097/pid_6879/cgroup.procs: No such file or directory
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{1234e22 u0 com.lge.launcher2/.Launcher t3} time:294402
D/[Concierge]Service( 2619): onStartCommand(). Type : 8
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/[Concierge]Service( 2619): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/Tethering( 1035): MasterInitialState.processMessage what=3
D/[Concierge]WidgetView( 2027): change position of spinner
I/NetworkMonitor( 5609): type=WIFI subType= reason=null isConnected=true
,D/[Concierge]Service( 2619): Update widget ID : 11
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[Concierge]WidgetView( 2027): initWebView(). Time : 1453126797369
D/[Concierge]Service( 2619): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2027): Return exist ConciergeWebView. Reuse : 585685816
D/[Concierge]WidgetView( 2027): State Change : null -> AccInBeforeState
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2027): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@31ae8ec3
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2027): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2027): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2027): Widget kill message received. Destory myself. My : 1453126531306, New one : 1453126797369
D/[Concierge]WidgetView( 2027): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2027): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
W/ContextImpl( 7568): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7568): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7568): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7568): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2027): Timeline: Activity_idle id: android.os.BinderProxy@3477827 time:294593
,I/WebViewFactory( 7568): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7568): Loading: webviewchromium
I/LibraryLoader( 7568): Time to load native libraries: 3 ms (timestamps 4678-4681)
I/LibraryLoader( 7568): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7568): Binding Chromium to main looper Looper (main, tid 1) {1fca6c75}
,I/LibraryLoader( 7568): Expected native library version number "",actual native library version number ""
I/chromium( 7568): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7568): Initializing chromium process, renderers=0
W/art     ( 7568): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  312): registerClient() client 0xb14fd5c0, uid 10093
,W/AudioManagerAndroid( 7568): Requires BLUETOOTH permission
I/chromium( 2027): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/chromium( 7568): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7568): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7568): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7568): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7568): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7568): Build Date: 12/12/14 금
I/Adreno-EGL( 7568): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7568): Remote Branch: 
I/Adreno-EGL( 7568): Local Patches: 
I/Adreno-EGL( 7568): Reconstruct Branch: 
,I/GBoardtInterface( 2027): onReloaded()
I/GBoardWebViewClient( 2027): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3769): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3769): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1900): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3769): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3769): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1900): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3769): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3769): onEvent() : ACTION_BOARD_ENABLED
,D/LIA_Informant_Tips_FormEventRepository( 3769): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3769): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3769): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/NSApplication( 7568): Starting up...
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max

```
