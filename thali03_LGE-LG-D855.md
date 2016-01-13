#### Test 55902202f27eba5_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 278256948973; DSPS: 9258738; Offset : -4309675498
,D/AndroidRuntime( 7120): 
D/AndroidRuntime( 7120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7120): CheckJNI is OFF
D/AndroidRuntime( 7120): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1969): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{26b57608 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{26b57608 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7135 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7120): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{36d64c63 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{1c16e060 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7135): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7135): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7135): Loading: webviewchromium
I/LibraryLoader( 7135): Time to load native libraries: 4 ms (timestamps 2649-2653)
I/LibraryLoader( 7135): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7135): Binding Chromium to main looper Looper (main, tid 1) {1d24e4d3}
I/LibraryLoader( 7135): Expected native library version number "",actual native library version number ""
I/chromium( 7135): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7135): Initializing chromium process, renderers=0
W/art     ( 7135): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  312): registerClient() client 0xb1427080, uid 10311
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a9ba252:true
W/chromium( 7135): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7135): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7135): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7135): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7135): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7135): Build Date: 12/12/14 금
I/Adreno-EGL( 7135): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7135): Remote Branch: 
I/Adreno-EGL( 7135): Local Patches: 
I/Adreno-EGL( 7135): Reconstruct Branch: 
W/chromium( 7135): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7135): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7135): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7135): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7135): CordovaWebView is running on device made by: LGE
W/art     ( 7135): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7135): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7135): Render dirty regions requested: true
I/OpenGLRenderer( 7135): Initialized EGL, version 1.4
D/OpenGLRenderer( 7135): Enabling debug mode 0
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{1769e1a1 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 7135): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{1faf07c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7135): LgDataFeature() Constructor: none
D/LgDataFeature( 7135): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1462): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1462): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1462):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1462): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eeee937,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +639ms (total +735ms)
I/Timeline( 7135): Timeline: Activity_idle id: android.os.BinderProxy@440a8c3 time:283088
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{1769e1a1 u0 com.test.thalitest/.MainActivity t4} time:283089
I/chromium( 7135): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7135): 
D/JsMessageQueue( 7135): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7135): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435073280
D/JX-Cordova( 7135): jxcore cordova android initializing
E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7135): Initializing JXcore engine
W/jxcore-log( 7135): JXcore engine is ready
,W/jxcore-log( 7135): Starting JXcore engine
,W/.test.thalitest( 7135): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7411]" dev="sockfs" ino=7411 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7135): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7135): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10044]" dev="sockfs" ino=10044 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7135): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7135): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32545]" dev="sockfs" ino=32545 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7135): Background sticky concurrent mark sweep GC freed 124584(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.842ms total 223.385ms
,W/jxcore-log( 7135): Platform android
W/jxcore-log( 7135): 
W/jxcore-log( 7135): Process ARCH arm
W/jxcore-log( 7135): 
,I/jxcore-log( 7135): JXcore Cordova bridge is ready!
I/jxcore-log( 7135): 
W/jxcore-log( 7135): JXcore engine is started
,I/jxcore-log( 7135): Toggling radios to true
I/jxcore-log( 7135): 
,D/BluetoothAdapter( 7135): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7135, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7135, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7135, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [286,664,428 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7135, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7135): Radios toggled
I/jxcore-log( 7135): 
I/jxcore-log( 7135): My device name is: LGE-LG-D855
I/jxcore-log( 7135): 
I/wpa_supplicant( 2705): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
D/Tethering( 1038): InitialState.processMessage what=4
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7234 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2140): Read error: ssl=0xaf4d2a00: I/O error during system call, Connection timed out
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [286,823,215 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2705): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
V/NativeCrypto( 2140): SSL shutdown failed: ssl=0xaf4d2a00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286827
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>,
,E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286840
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286867  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286868  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524292
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286885  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286891  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
,D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7234): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7234): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7234): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7234): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7234): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED,
D/UsbSettingsReceiver( 7234): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7234): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7234): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7234): [AUTORUN] getUsbConnected() : connected=true,
,D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7234): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7234): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7272 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6501:com.android.defcontainer/u0a4 (adj 15): empty #17
I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 18.881ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 17.345ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 15.445ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6501/cgroup.procs: No such file or directory
,I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7272): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7234): LgDataFeature() Constructor: none
D/LgDataFeature( 7234): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7296 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6616:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6616/cgroup.procs: No such file or directory
,W/ResourcesManager( 7296): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7296): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7296): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7296): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7296): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7296): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7296): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7296): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7296): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7296): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7296): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7272): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7272): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7272): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
,D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7296): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7296): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7296): LgDataFeature() Constructor: none
,D/LgDataFeature( 7296): LgDataFeature() Constructor Done, null
V/SoundPool( 7296): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7296): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7296): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 7296): doLoad: loading sample sampleID=1
I/QRemote ( 7296): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7296): Start decode
V/MediaPlayer[Native]( 7296): decode(32, 10857164, 17813)
V/MediaPlayerService(  312): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  312): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  312): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  312): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  312): player type = 3
V/AwesomePlayer(  312): AwesomePlayer create()
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): setAudioSink() 
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/Utils   (  312): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  312): setDataSource_l dataSource
V/LGParserOSAL(  312): SniffLGParser start
V/LGParserOSAL(  312): MainType:5, SubType=0
V/LGParserOSAL(  312): #### check Mime : application/ogg
V/LGParserOSAL(  312): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  312): Use LGExtractor :application/ogg 
,D/UEI.SmartControl( 6852): QS Service created
D/QRemote ( 7296): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7296): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7296): Create singleton instance
I/UEI.SmartControl( 6852): Service initServices...
,D/UEI.SmartControl( 6852): QS start get config
V/LGParserOSAL(  312): supported mime: application/ogg
V/AwesomePlayer(  312): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  312): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  312): mBitrate = -1 bits/sec
V/AwesomePlayer(  312): AudioTrack Setting
V/AwesomePlayer(  312): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  312): setAudioSource() 
V/MediaPlayerService(  312): prepare
V/AwesomePlayer(  312): prepareAsync_l() 
V/MediaPlayerService(  312): wait for prepare
V/AwesomePlayer(  312): onPrepareAsyncEvent() 
V/AwesomePlayer(  312): initAudioDecoder() 
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  312): isAudioPlaybackHookOn() false
V/AwesomePlayer(  312): getUseOffload() = 0 
V/OMXCodec(  312): OMXCodec::Create
V/OMXCodec(  312): findMatchingCodecs()
V/OMXCodec(  312): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  312): matchingCodecs.size()=1
V/OMXCodec(  312): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  312): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  312): LG Codec Adapter start
V/OMXCodec(  312): OMXCodec Createtor
V/OMXCodec(  312): setComponentRole
V/OMXCodec(  312): configureCodec protected=0
V/LGCodecAdapter(  312): called getLGCodecSpecificData
V/LGCodecOSAL(  312): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMSG
V/LGCodecOSAL(  312): Not support LGCodec
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  312): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  312): Could not offload audio decode, try pcm offload
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  312): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  312): init()
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  312): allocateBuffers
V/OMXCodec(  312): allocateBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb57c31f0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3470 on output port
V/OMXCod,ec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3510 on output port
V/OMXCodec(  312): init() mAsyncCompletion wait!!! 
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  312): init() mAsyncCompletion wait!!! 
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  312): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  312): finishAsyncPrepare_l() 
V/AudioCache(  312): notify(0xb5474980, 5, 0, 0)
V/AudioCache(  312): ignored
V/AudioCache(  312): notify(0xb5474980, 1, 0, 0)
V/AudioCache(  312): prepared
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): start
V/AwesomePlayer(  312): play_l() 
V/AwesomePlayer(  312): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  312): createAudioPlayer_l
V/AwesomePlayer(  312): seekAudioIfNecessary_l() 
V/AwesomePlayer(  312): startAudioPlayer_l() 
D/AudioPlayer(  312): start of Playback, useOffload 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  312): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815344
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815984
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816144
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  312): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3470 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb57c31f0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  312): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  312): notify(0xb5474980, 6, 0, 0)
V/AudioCache(  312): ignored
V/MediaPlayerService(  312): wait for playback complete
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab700000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab701000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab702000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab703000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab704000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab705000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab706000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab707000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab708000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab709000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70a000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70b000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70c000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70d000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70e000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab70f000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab710000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab711000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab712000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab713000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab714000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab715000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab716000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab717000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab718000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab719000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71a000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71b000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71c000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71d000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71e000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab71f000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab720000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab721000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab722000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab723000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab724000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab725000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab726000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab727000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab728000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab729000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72a000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72b000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72c000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72d000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72e000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab72f000, 0xb57db000, 4096)
,V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab730000, 0xb57db000, 4096)
V/AudioCache(  312): write(0xb57db000, 4096)
V/AudioCache(  312): memcpy(0xab731000, 0xb57db000, 4096)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  312): postAudioEOS() 
V/AudioCache(  312): write(0xb57db000, 280)
V/AudioCache(  312): memcpy(0xab732000, 0xb57db000, 280)
V/AwesomePlayer(  312): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  312): onStreamDone
V/AwesomePlayer(  312): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  312): notify(0xb5474980, 2, 0, 0)
V/AudioCache(  312): playback complete
V/AwesomePlayer(  312): pause_l() 
V/AudioCache(  312): notify(0xb5474980, 7, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  312): Pause Playback at 1068125
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/AudioPlayer(  312): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb57c31f0 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3470 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  312): AudioPlayer releasing audio source
D/AudioPlayer(  312): AudioPlayer done releasing audio source
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): ~AwesomePlayer call
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/SoundPool( 7296): close(32)
V/SoundPool( 7296): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7296): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:154
,I/UEI.SmartControl( 6852): Supports setup maps: true
,D/UEI.SmartControl( 6852): QS start statue = true Error code = 0
I/UEI.SmartControl( 6852): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6852): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6852): ### init IR Blaster...
D/serial_port( 6852): Configuring serial port
E/UEI.SmartControl( 6852): UEIBLaster setting for 616
I/UEI.SmartControl( 6852): Setting serial record hearder size = 2
I/UEI.SmartControl( 6852): configuring settings for MAXQ616
I/UEI.SmartControl( 6852): Get version...
D/UEI.SmartControl( 6852): serial port data available: 21
,D/UEI.SmartControl( 6852): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6852): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6852): QS saving settings...
,D/UEI.SmartControl( 6852): IR Blaster version: 25672567
,D/UEI.SmartControl( 6852): serial port data available: 4
,I/UEI.SmartControl( 6852): Device manager: loading config....
,D/UEI.SmartControl( 6852): ----------- loading internal config...
W/ContextImpl( 6852): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6852): Services init done
D/UEI.SmartControl( 6852): QS Service init finished
D/UEI.SmartControl( 6852): QS Service version name: 2.1.91
D/UEI.SmartControl( 6852): QS Service version code: 201091
D/UEI.SmartControl( 6852): Service requested: Control
D/UEI.SmartControl( 6852): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6852): Loading SETTINGS...
,D/UEI.SmartControl( 6852): Internal service binding...
I/QRemote ( 7296): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6852): ------ IControl API: 11
D/UEI.SmartControl( 6852): File observer start...
E/UEI.SmartControl( 6852): IR Port is disabled: false
D/UEI.SmartControl( 6852): Starting file observer...
I/UEI.SmartControl( 6852): Registering callback...
I/UEI.SmartControl( 6852): ------ IControl API: 19
I/UEI.SmartControl( 6852): Registering Services Ready callback...
D/UEI.SmartControl( 6852): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6852): Notify AllClients services are ready: 0
I/QRemote ( 7296): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6852): -----service ready thread exits
,D/QRemote ( 7296): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7296): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7296): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,D/QRemote ( 7296): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6852): ------ IControl API: 8
D/QRemote ( 7296): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7296): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7296): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7296): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7296): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7296): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 7296): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 7296): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6641:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6641/cgroup.procs: No such file or directory
,V/QRemote ( 7296): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE,
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7296): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 7296): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452699558772]
D/QRemote ( 7296): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 7296): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7296): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0,
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7296): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7296): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2705): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289016  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289043  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
,V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
,D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7296): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
I/wpa_supplicant( 2705): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289117  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289117  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2705): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2705): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289121
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289121
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289122
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289122
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289123
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289123  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289133  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7234): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7234): [AUTORUN] sys.usb.state = ptp_only,adb
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289140  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289141  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289142
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289142
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/UsbSettingsReceiver( 7234): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7234): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7234): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7234): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7234): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  308): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289187  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289187  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289188  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289191  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289192  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289192  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@932d9c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@932d9c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up wlan0
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2705): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1038): SET ps 1: returned true
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1038): ignoring duplicate network state non-change
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 1
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  308): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
W/dsqn    ( 7359): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7359): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
,D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 7359): DSQN ssw
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7296): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7296): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7296): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7296): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7272): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7272): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7234): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7234): MCCMNC not supported: null
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/QRemote ( 7296): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7296): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7296): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7296): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7296): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:39:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699559566], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699559541]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7365): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7365): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7365): version 5.5.6 starting
E/dhcpcd  ( 7365): get_duid: m
D/dhcpcd  ( 7365): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7365): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7365): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7365): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7365): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7365): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7365): wlan0: sending REQUEST (xid 0x4e9e607e), next in 4.59 seconds
I/dhcpcd  ( 7365): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
I/dhcpcd  ( 7365): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7365): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7365): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7365): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7365): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7365): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7365): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7365): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/Tethering( 1038): MasterInitialState.processMessage what=3
W/ContextImpl( 6587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5469): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5469): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7409 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7409): onCreate
W/AppUp4:DB( 7409):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7409):  setFingerPrint start
I/AppUp4:DB( 7409):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7409):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7409):  SDK version = 21
I/AppUp4:DB( 7409):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7409): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7409): onReceive
D/LgDataFeature( 7409): LgDataFeature() Constructor: none
D/LgDataFeature( 7409): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2d2adf09
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7409): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7409): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7409): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7409): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6661:com.android.contacts/u0a19 (adj 15): empty #17
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6661/cgroup.procs: No such file or directory
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=919583859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{142a9761 type 2 when 290254 com.google.android.gms} when 290254
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3432): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3432): DownloadService onCreate
I/DownloadManager( 3432): in removeSpuriousFiles
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@2920265d on behalf of 3432
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3432): in trimDatabase
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@174edbd2 on behalf of 3432
V/DownloadManager( 3432): DownloadService onStartCommand
,V/DownloadManager( 3432): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@20bdcb59 on behalf of 3432
V/DownloadManager( 3432): processing inserted download 1
V/DownloadManager( 3432): processing inserted download 4
V/DownloadManager( 3432): processing inserted download 7
V/DownloadManager( 3432): processing inserted download 8
D/eas_req ( 6685): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3432): processing inserted download 9
V/DownloadManager( 3432): processing inserted download 10
V/DownloadManager( 3432): processing inserted download 16
,V/DownloadManager( 3432): processing inserted download 17
V/DownloadManager( 3432): processing inserted download 18
V/DownloadManager( 3432): processing inserted download 21
I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7445 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3432): DownloadService onDestroy
I/HubEmail( 6685): JNI_OnLoad()
I/HubEmail( 6685): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6685): registerNatives()
I/HubEmail( 6685): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6685): registerNativeMethods()
I/HubEmail( 6685): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6685): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3368): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7469 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7489 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6709:com.android.gallery3d/u0a27 (adj 15): empty #17
V/FormManager( 7445): There are no updated forms. The schedule will be deleted.
V/FormManager( 7445): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6709/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 6735:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524295
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7508 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6735/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 6765:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6765/cgroup.procs: No such file or directory
,I/art     ( 7508): Almond Protected OAT
,D/WeatherApplication( 7508): removeAccount
,D/WeatherApplication( 7508): Account.length = 0
E/WeatherApplication( 7508): OPERATOR:OPEN
D/WeatherAncestor( 7508): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:21
D/Weather.Utils( 7508): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7508): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7508): 2 : This is isUpdating : false
,D/WeatherAncestor( 7508): connectivity changed - connection : true
D/WeatherService( 7508): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7508): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7508): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7508): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7508): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7508): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:21
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7529 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6831:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6831/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7529): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/WebViewFactory( 7529): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7529): Loading: webviewchromium
,I/LibraryLoader( 7529): Time to load native libraries: 4 ms (timestamps 2041-2045)
I/LibraryLoader( 7529): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7529): Binding Chromium to main looper Looper (main, tid 1) {2bf4ac58}
I/LibraryLoader( 7529): Expected native library version number "",actual native library version number ""
I/chromium( 7529): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7529): Initializing chromium process, renderers=0
W/art     ( 7529): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7529): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7529): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7529): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  312): registerClient() client 0xb54f5e20, uid 10093
W/AudioManagerAndroid( 7529): Requires BLUETOOTH permission
I/Adreno-EGL( 7529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7529): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7529): Build Date: 12/12/14 금
I/Adreno-EGL( 7529): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7529): Remote Branch: 
I/Adreno-EGL( 7529): Local Patches: 
I/Adreno-EGL( 7529): Reconstruct Branch: 
,I/NSApplication( 7529): Starting up...
,I/ActivityManager( 1038): Killing 6876:com.lge.bnr/1000 (adj 15): empty #17
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6876/cgroup.procs: No such file or directory
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5469): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2315): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2315): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7409): onReceive
D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2d2adf09
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3432): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3432): DownloadService onCreate
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3432): in removeSpuriousFiles
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     ( 1038): Explicit concurrent mark sweep GC freed 86513(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.302ms total 126.012ms
,V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@e5a07ff on behalf of 3432
,I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3432): in trimDatabase
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@38ff49cc on behalf of 3432
,I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LgeMiscReceiver( 3368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3368): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3432): DownloadService onStartCommand
V/DownloadManager( 3432): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LgeMiscReceiver( 3368): networkInfo.isConnected() = false
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@3651251b on behalf of 3432
V/DownloadManager( 3432): processing inserted download 1
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3432): processing inserted download 4
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3432): processing inserted download 7
V/DownloadManager( 3432): processing inserted download 8
D/WeatherAncestor( 7508): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:22
,D/Weather.Utils( 7508): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7508): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7508): 2 : This is isUpdating : false
D/WeatherAncestor( 7508): connectivity changed - connection : true
D/WeatherService( 7508): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a4efb2f
D/ForecastDataCache( 7508): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7508): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7508): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7508): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7508): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:22
V/DownloadManager( 3432): processing inserted download 9
V/DownloadManager( 3432): processing inserted download 10
V/DownloadManager( 3432): processing inserted download 16
V/DownloadManager( 3432): processing inserted download 17
V/DownloadManager( 3432): processing inserted download 18
V/DownloadManager( 3432): processing inserted download 21
V/DownloadManager( 3432): DownloadService onDestroy
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/FormManager( 7445): There are no updated forms. The schedule will be deleted.
W/Kids    ( 2315): [AccountUtils] Account not ready
W/Kids    ( 2315): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2315): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2315): 	at java.lang.Thread.run(Thread.java:818)
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
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
V/FormManager( 7445): Alarm would be updated, because LastCheckTime has been updated.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 2315): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1c8c8c91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=919583859 [*alarm*], flags=0x0
,D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
W/ContextImpl( 6587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7409): onReceive
D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2d2adf09
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3432): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3432): DownloadService onCreate
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
I/DownloadManager( 3432): in removeSpuriousFiles
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@1c8c8c91 on behalf of 3432
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3432): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3432): in trimDatabase
V/DownloadManager( 3432): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@3d237f6 on behalf of 3432
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3368): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3368): networkInfo.isConnected() = true
D/PhoneState( 3368): setPdpRejectCasuse : false
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3432): DownloadService onStartCommand
V/DownloadManager( 3432): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3432): created cursor android.database.sqlite.SQLiteCursor@edc60cd on behalf of 3432
D/WeatherAncestor( 7508): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:22
V/DownloadManager( 3432): processing inserted download 1
V/DownloadManager( 3432): processing inserted download 4
V/DownloadManager( 3432): processing inserted download 7
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3432): processing inserted download 8
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3432): processing inserted download 9
V/DownloadManager( 3432): processing inserted download 10
D/Weather.Utils( 7508): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7508): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7508): 2 : This is isUpdating : false
D/WeatherAncestor( 7508): connectivity changed - connection : true
D/WeatherService( 7508): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1a4efb2f
V/DownloadManager( 3432): processing inserted download 16
V/DownloadManager( 3432): processing inserted download 17
V/DownloadManager( 3432): processing inserted download 18
V/DownloadManager( 3432): processing inserted download 21
D/ForecastDataCache( 7508): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7508): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7508): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7508): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7508): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:39:22
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
W/Kids    ( 2315): [AccountUtils] Account not ready
W/Kids    ( 2315): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2315): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2315): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/DownloadManager( 3432): DownloadService onDestroy
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1c8c8c91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7445): There are no updated forms. The schedule will be deleted.
V/FormManager( 7445): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2315): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2315): [AccountUtils] Account not ready
W/Kids    ( 2315): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2315): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2315): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2315): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2315): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{1c8c8c91 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GoogleURLConnFactory( 2140): Using platform SSLCertificateSocketFactory
,W/Uploader( 2140): No account for auth token provided
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
,D/GCM     ( 2140): Connected
,D/GCM     ( 2140): Message class com.google.f.a.a.p
,W/Uploader( 2140): No account for auth token provided
,W/Uploader( 2140): No account for auth token provided
,W/Uploader( 2140): No account for auth token provided
W/Uploader( 2140): No account for auth token provided
,D/UEI.SmartControl( 6852): Internal timer expired: 4
D/UEI.SmartControl( 6852): unbind internal service
,D/serial_port( 6852): close(fd = 24)
W/Uploader( 2140):  no longer exists, so no auth token.
,I/UEI.SmartControl( 6852): Serial port is closed.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  308): res_queryN name = www.google.com succeed
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7135): Test app app.js loaded
I/jxcore-log( 7135): 
,I/chromium( 7135): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7135): 
,I/chromium( 7135): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7135): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 7135): --= Surplus to requirements =--
I/jxcore-log( 7135): 
I/jxcore-log( 7135): ****TEST TOOK:  ms ****
I/jxcore-log( 7135): 
I/jxcore-log( 7135): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7135): 
,D/AndroidRuntime( 7637): 
D/AndroidRuntime( 7637): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7637): CheckJNI is OFF
,D/AndroidRuntime( 7637): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7135:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1038): Skipping PackageSetting{2746ef21 com.example.hello/10319} due to missing metadata
,I/WindowState( 1038): WIN DEATH: Window{1faf07c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{1faf07c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{1769e1a1 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{3ae73eda 7135:com.test.thalitest/u0a311}, curProc for 7135: null
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{1769e1a1 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{1769e1a1 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2087): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{185af919 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2087): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2087): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{18f7ddde co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/KeyguardModel( 1462): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/art     ( 4594): Explicit concurrent mark sweep GC freed 16102(914KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 591us total 54.347ms
D/LIA_Service_RemotePackageHandler( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3727): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4538): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4538): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
D/ActionManagerService( 1924): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3727): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/PostponalbeReceiver( 6587): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4538): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4538): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4538): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4538): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4538): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4538): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4538): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4538): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/administrator( 1038): Handling package changes for user 0
,D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
,I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7673 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2087): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2087): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2087): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1462): onReceive = android.intent.action.PACKAGE_REMOVED
D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1924): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3727): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3727): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2087): , create_time: 1430558575574
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2087): , create_time: 1430558575600
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2087): , create_time: 1452175675684
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
,D/WallpaperManager( 2087): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1462): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1462): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eeee937,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 7409): added Exclude : com.test.thalitest
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7692 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]EVENT( 2087): [Launcher.java:5349:onStop()]onStop
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
,I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1462): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1462): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1462):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1462): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     ( 2087): Background partial concurrent mark sweep GC freed 6850(296KB) AllocSpace objects, 4(981KB) LOS objects, 28% free, 78MB/110MB, paused 12.725ms total 40.051ms
,I/LockScreenSettings( 7673): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1462): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1462): createShortcutInfo...
D/KeyguardModel( 1462): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1462): createShortcutInfo...
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/art     ( 1038): Explicit concurrent mark sweep GC freed 25114(1611KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 3.945ms total 356.777ms
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/AndroidRuntime( 7637): Shutting down VM
,I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/KeyguardModel( 1462): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1462): createShortcutInfo...
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1462): createShortcutInfo...
,I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{38c48d60 u0 com.lge.launcher2/.Launcher t3} time:295503
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager( 1038): Killing 6900:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2087): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/KeyguardModel( 1462): handleShortcutListChanged...
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6900/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2615): onStartCommand(). Type : 8
,D/[Concierge]WidgetView( 2087): change position of spinner
D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2615): Update widget ID : 11
D/KeyguardModel( 1462): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1462): createShortcutInfo...
I/[Concierge]WidgetView( 2087): initWebView(). Time : 1452699565745
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
,D/KeyguardModel( 1462): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1462): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1462): createShortcutInfo...
I/SystemConfig( 7692): BUILD Country: EU
I/SystemConfig( 7692): BUILD Operator: OPEN
D/KeyguardModel( 1462): handleShortcutListChanged...
,I/[Concierge]WebView( 2087): Return exist ConciergeWebView. Reuse : 160973779
D/[Concierge]WidgetView( 2087): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2087): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1d144bfb
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2087): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2087): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2087): Widget kill message received. Destory myself. My : 1452699298071, New one : 1452699565745
D/[Concierge]WidgetView( 2087): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2087): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1038): Killing 6999:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2087): Timeline: Activity_idle id: android.os.BinderProxy@11d0ab32 time:295739
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6999/cgroup.procs: No such file or directory
,I/SystemConfig( 7692): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7692): existFile = false
I/SystemConfig( 7692): canReadFile = false
I/SystemConfig( 7692): systemFeature RCS result false
D/SystemConfig( 7692): refreshRcsSupport() :false
I/PackageChangeReceiver( 6685): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2168): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2168): (2570) os_unix.c:31441: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj9277F39DA) - 
,D/ContactsProvider2ForLG( 2168): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2168): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
D/ContactsProvider2ForLG( 2168): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2168): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2168): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
D/ContactsProvider2ForLG( 2168): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
D/ContactsProvider2ForLG( 2168): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:525)
D/ContactsProvider2ForLG( 2168): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:414)
D/ContactsProvider2ForLG( 2168): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2168): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2168): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2168): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2168): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2168): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2168): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2168): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2168): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2168): Process: android.process.acore, PID: 2168
E/AndroidRuntime( 2168): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2168): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2168): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2168): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2168): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2168): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2168): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2168): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2168): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2168): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2168): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2168): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2168): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2168): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2168): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2168): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2168): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7717 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/Process ( 2168): Sending signal. PID: 2168 SIG: 9
E/DropBoxManagerService( 1038): Can't write: system_app_crash
E/DropBoxManagerService( 1038): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1038): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1038): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1038): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1038): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1038): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1038): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1038): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1038): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1038): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1038): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1038): 	... 5 more
,I/chromium( 2087): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2087): onReloaded()
,I/GBoardWebViewClient( 2087): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1038): Process android.process.acore (pid 2168) has died
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
V/BoardContentProvider( 3727): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3727): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1924): notifyUserLog: 1000001

```
