#### Test 549702619369e5e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 256513229865; DSPS: 8546031; Offset : -4306700838
,D/AndroidRuntime( 7176): 
D/AndroidRuntime( 7176): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7176): CheckJNI is OFF
D/AndroidRuntime( 7176): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1921): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1b204a29 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1b204a29 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7196 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7176): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1832): Display #0 changed.
D/SplitWindowPolicy( 1921): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1921): topRunningActivity=ActivityInfo{38852581 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1921): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1921): topRunningActivity=ActivityInfo{24e47626 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7196): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7196): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7196): Loading: webviewchromium
I/LibraryLoader( 7196): Time to load native libraries: 3 ms (timestamps 3838-3841)
I/LibraryLoader( 7196): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7196): Binding Chromium to main looper Looper (main, tid 1) {21e3a571}
I/LibraryLoader( 7196): Expected native library version number "",actual native library version number ""
I/chromium( 7196): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7196): Initializing chromium process, renderers=0
W/art     ( 7196): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  332): registerClient() client 0xb14fd280, uid 10311
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23f72d6b:true
W/chromium( 7196): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7196): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7196): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7196): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7196): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7196): Build Date: 12/12/14 금
I/Adreno-EGL( 7196): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7196): Remote Branch: 
I/Adreno-EGL( 7196): Local Patches: 
I/Adreno-EGL( 7196): Reconstruct Branch: 
,W/chromium( 7196): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7196): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7196): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7196): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7196): CordovaWebView is running on device made by: LGE
,W/art     ( 7196): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7196): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7196): Render dirty regions requested: true
,I/OpenGLRenderer( 7196): Initialized EGL, version 1.4
D/OpenGLRenderer( 7196): Enabling debug mode 0
,D/Atlas   ( 7196): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{82a710d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{280e41ae u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7196): LgDataFeature() Constructor: none
D/LgDataFeature( 7196): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d8359fe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1450): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1450): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1450):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1450): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +633ms (total +742ms)
,I/Timeline( 7196): Timeline: Activity_idle id: android.os.BinderProxy@17cce1 time:264293
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{280e41ae u0 com.test.thalitest/.MainActivity t4} time:264295
I/chromium( 7196): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7196): 
,D/JsMessageQueue( 7196): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7196): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435087616
,D/JX-Cordova( 7196): jxcore cordova android initializing
E/GBMv2   (  349): DFP En is all cleared set to be enabled
E/GBMv2   (  349): Set value is all cleared set the max
I/GBMv2   (  349): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7196): Initializing JXcore engine
W/jxcore-log( 7196): JXcore engine is ready
,W/jxcore-log( 7196): Starting JXcore engine,
W/.test.thalitest( 7196): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8391]" dev="sockfs" ino=8391 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7196): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7196): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10435]" dev="sockfs" ino=10435 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7196): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7196): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34204]" dev="sockfs" ino=34204 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 7196): Background sticky concurrent mark sweep GC freed 124643(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.636ms total 119.995ms
,W/jxcore-log( 7196): Platform android
W/jxcore-log( 7196): 
W/jxcore-log( 7196): Process ARCH arm
W/jxcore-log( 7196): 
,I/jxcore-log( 7196): JXcore Cordova bridge is ready!
I/jxcore-log( 7196): 
W/jxcore-log( 7196): JXcore engine is started
,I/jxcore-log( 7196): Toggling radios to true
I/jxcore-log( 7196): 
,D/BluetoothAdapter( 7196): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7196, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7196, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7196, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [266,642,154 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7196, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7196): Radios toggled
I/jxcore-log( 7196): 
I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/Tethering( 1037): InitialState.processMessage what=4
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  328): Clearing all IP addresses on wlan0
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7282 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2050): Read error: ssl=0xaa6f3e00: I/O error during system call, Connection timed out
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/WifiHS20( 1037): hidePasspointNotification off =false
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
V/WfdStateTracker( 1921): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [266,786,610 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=266799
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=266799
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
V/NativeCrypto( 2050): SSL shutdown failed: ssl=0xaa6f3e00: I/O error during system call, Broken pipe
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  328): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=266856  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/ResourcesManager( 7282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ResourcesManager( 7282): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/WifiHS20( 1037): hidePasspointNotification off =false
W/ResourcesManager( 7282): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7282): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/ResourcesManager( 7282): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 7282): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=266857  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1450): CM callback handler got msg 524292
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=266865  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/WifiHS20( 1037): hidePasspointNotification off =false
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1832): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecifi,ed), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1832):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=266879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/TelephonyIcons( 1450): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1450): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7282): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7282): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7282): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-181ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsControl( 7282): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7282): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7282): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6753:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6753/cgroup.procs: No such file or directory
,I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7282): LgDataFeature() Constructor: none
,D/LgDataFeature( 7282): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7340 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6648:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6648/cgroup.procs: No such file or directory
W/ResourcesManager( 7340): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 7340): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 7340): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7340): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7340): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7340): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7340): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7340): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7340): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7340): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7316): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7340): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7340): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7340): LgDataFeature() Constructor: none
D/LgDataFeature( 7340): LgDataFeature() Constructor Done, null
V/SoundPool( 7340): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7340): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7340): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7340): doLoad: loading sample sampleID=1
I/QRemote ( 7340): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 7340): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/SoundPool( 7340): Start decode
V/MediaPlayer[Native]( 7340): decode(31, 10857164, 17813)
D/UEI.SmartControl( 6811): QS Service created
V/MediaPlayerService(  332): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  332): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  332): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  332): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  332): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  332): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  332): player type = 3
V/AwesomePlayer(  332): AwesomePlayer create()
V/AwesomePlayer(  332): reset_l() 
V/AwesomePlayer(  332): cancelPlayerEvents
V/AwesomePlayer(  332): setAudioSink() 
V/AwesomePlayer(  332): reset_l() 
V/AudioCache(  332): notify(0xb5474580, 8, 0, 0)
V/AudioCache(  332): ignored
V/AwesomePlayer(  332): cancelPlayerEvents
D/Utils   (  332): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  332): setDataSource_l dataSource
V/LGParserOSAL(  332): SniffLGParser start
V/LGParserOSAL(  332): MainType:5, SubType=0
V/LGParserOSAL(  332): #### check Mime : application/ogg
V/LGParserOSAL(  332): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  332): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6811): Service initServices...
D/UEI.SmartControl( 6811): QS start get config
E/QRemote ( 7340): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  332): supported mime: application/ogg
V/AwesomePlayer(  332): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  332): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  332): mBitrate = -1 bits/sec
V/AwesomePlayer(  332): AudioTrack Setting
V/AwesomePlayer(  332): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  332): setAudioSource() 
V/MediaPlayerService(  332): prepare
V/AwesomePlayer(  332): prepareAsync_l() 
V/MediaPlayerService(  332): wait for prepare
V/AwesomePlayer(  332): onPrepareAsyncEvent() 
V/AwesomePlayer(  332): initAudioDecoder() 
W/Utils   (  332): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  332): isOffloadSupported()
V/AudioPolicyManager(  332): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  332): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  332): isAudioPlaybackHookOn() false
V/AwesomePlayer(  332): getUseOffload() = 0 
V/OMXCodec(  332): OMXCodec::Create
V/OMXCodec(  332): findMatchingCodecs()
V/OMXCodec(  332): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  332): matchingCodecs.size()=1
V/OMXCodec(  332): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  332): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  332): LG Codec Adapter start
V/OMXCodec(  332): OMXCodec Createtor
V/OMXCodec(  332): setComponentRole
V/OMXCodec(  332): configureCodec protected=0
V/LGCodecAdapter(  332): called getLGCodecSpecificData
V/LGCodecOSAL(  332): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  332): Called LGconfigureCodecMETA
V/LGCodecOSAL(  332): Called LGconfigureCodecMSG
V/LGCodecOSAL(  332): Not support LGCodec
V/OMXCodec(  332): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  332): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  332): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  332): Could not offload audio decode, try pcm offload
W/Utils   (  332): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  332): isOffloadSupported()
V/AudioPolicyManager(  332): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  332): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  332): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  332): init()
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  332): allocateBuffers
V/OMXCodec(  332): allocateBuffersOnPort portIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  332): allocateBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  332): init() mAsyncCompletion wait!!! 
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  332): init() mAsyncCompletion wait!!! 
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  332): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  332): finishAsyncPrepare_l() 
V/AudioCache(  332): notify(0xb5474580, 5, 0, 0)
V/AudioCache(  332): ignored
V/AudioCache(  332): notify(0xb5474580, 1, 0, 0)
V/AudioCache(  332): prepared
V/AudioCache(  332): wait - success
V/MediaPlayerService(  332): start
V/AwesomePlayer(  332): play_l() 
V/AwesomePlayer(  332): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  332): createAudioPlayer_l
V/AwesomePlayer(  332): seekAudioIfNecessary_l() 
V/AwesomePlayer(  332): startAudioPlayer_l() 
D/AudioPlayer(  332): start of Playback, useOffload 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  332): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  332): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  332): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795744
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  332): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  332): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  332): allocateBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb1750380 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  332): open(48000, 2, 0x0, 1, 4)
V/LGMDMManager( 7340): Create singleton instance
V/AudioCache(  332): notify(0xb5474580, 6, 0, 0)
V/AudioCache(  332): ignored
V/MediaPlayerService(  332): wait for playback complete
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae806000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae807000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae808000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae809000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80a000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80b000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80c000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80d000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80e000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae80f000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae810000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae811000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae812000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae813000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae814000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae815000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae816000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae817000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae818000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae819000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81a000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81b000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81c000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81d000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81e000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae81f000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae820000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae821000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae822000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae823000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae824000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae825000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae826000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae827000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae828000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae829000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82a000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82b000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82c000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82d000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82e000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae82f000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae830000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae831000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae832000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae833000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae834000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae835000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae836000, 0xb57c8000, 4096)
V/AudioCache(  332): write(0xb57c8000, 4096)
V/AudioCache(  332): memcpy(0xae837000, 0xb57c8000, 4096)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  332): postAudioEOS() 
V/AudioCache(  332): write(0xb57c8000, 280)
V/AudioCache(  332): memcpy(0xae838000, 0xb57c8000, 280)
V/AwesomePlayer(  332): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  332): onStreamDone
V/AwesomePlayer(  332): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  332): notify(0xb5474580, 2, 0, 0)
V/AudioCache(  332): playback complete
V/AwesomePlayer(  332): pause_l() 
V/AudioCache(  332): notify(0xb5474580, 7, 0, 0)
V/AudioCache(  332): ignored
V/AwesomePlayer(  332): cancelPlayerEvents
V/AudioCache(  332): wait - success
V/MediaPlayerService(  332): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  332): Pause Playback at 1068125
V/AwesomePlayer(  332): reset_l() 
V/AudioCache(  332): notify(0xb5474580, 8, 0, 0)
V/AudioCache(  332): ignored
V/AwesomePlayer(  332): cancelPlayerEvents
D/AudioPlayer(  332): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb1750380 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  332): AudioPlayer releasing audio source
D/AudioPlayer(  332): AudioPlayer done releasing audio source
V/AwesomePlayer(  332): reset_l() 
V/AwesomePlayer(  332): cancelPlayerEvents
V/AwesomePlayer(  332): ~AwesomePlayer call
V/AwesomePlayer(  332): reset_l() 
V/AwesomePlayer(  332): cancelPlayerEvents
V/SoundPool( 7340): close(31)
V/SoundPool( 7340): pointer = 0x9fffd000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6127
I/UEI.SmartControl( 6811): Supports setup maps: true
D/UEI.SmartControl( 6811): QS start statue = true Error code = 0
I/UEI.SmartControl( 6811): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6811): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6811): ### init IR Blaster...
D/serial_port( 6811): Configuring serial port
E/UEI.SmartControl( 6811): UEIBLaster setting for 616
I/UEI.SmartControl( 6811): Setting serial record hearder size = 2
I/UEI.SmartControl( 6811): configuring settings for MAXQ616
I/UEI.SmartControl( 6811): Get version...
D/UEI.SmartControl( 6811): serial port data available: 21
D/UEI.SmartControl( 6811): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6811): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6811): QS saving settings...
D/UEI.SmartControl( 6811): IR Blaster version: 25672567
D/UEI.SmartControl( 6811): serial port data available: 4
W/ContextImpl( 6811): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6811): Services init done
D/UEI.SmartControl( 6811): QS Service init finished
D/UEI.SmartControl( 6811): QS Service version name: 2.1.91
D/UEI.SmartControl( 6811): QS Service version code: 201091
I/UEI.SmartControl( 6811): Device manager: loading config....
D/UEI.SmartControl( 6811): Service requested: Control
D/UEI.SmartControl( 6811): ----------- loading internal config...
E/UEI.SmartControl( 6811): Loading SETTINGS...
D/UEI.SmartControl( 6811): Request IControl service: devices are loaded...
I/QRemote ( 7340): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6811): ------ IControl API: 11
D/UEI.SmartControl( 6811): File observer start...
E/UEI.SmartControl( 6811): IR Port is disabled: false
D/UEI.SmartControl( 6811): Starting file observer...
D/UEI.SmartControl( 6811): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6811): Registering callback...
D/UEI.SmartControl( 6811): Internal service binding...
I/UEI.SmartControl( 6811): ------ IControl API: 19
I/UEI.SmartControl( 6811): Registering Services Ready callback...
I/UEI.SmartControl( 6811): Notify AllClients services are ready: 0
I/QRemote ( 7340): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6811): -----service ready thread exits
D/QRemote ( 7340): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7340): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7340): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7340): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6811): ------ IControl API: 8
D/QRemote ( 7340): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7340): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7340): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7340): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7340): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7340): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7340): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7340): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7340): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7340): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452292240303]
D/QRemote ( 7340): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6784:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 7340): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6784/cgroup.procs: No such file or directory
V/QRemote ( 7340): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7340): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7340): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2719): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=268947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=268967  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7340): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
,D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2719): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=269043  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=269043  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=269043
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=269043
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=269043
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=269044
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=269044
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=269044  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2719): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2719): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6592): WSAndroidSystem,IntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=269052  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=269055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=269056  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=269056
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=269056
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7282): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7282): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7282): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7282): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7282): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7282): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/UsbSettingsControl( 7282): [AUTORUN] setTetherStatus() : status=false
D/CommandListener(  328): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=269106  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=269106  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=269106  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=269109  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=269109  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=269109  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19d8f685 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19d8f685 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  328): Setting iface cfg
D/CommandListener(  328): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2719): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
,V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1037): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1921): handleWifiStateChangedEvent: 1
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1450): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1450): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  328): netlink response contains error (File exists)
,D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
,D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory-1( 1832): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1832):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 28
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, a,ction=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
,V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityManager.CallbackHandler( 1450): CM callback handler got msg 524290
W/dsqn    ( 7410): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7410): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
E/DSQN    ( 7410): DSQN ssw
,D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1450): null signal icon name: drawable/stat_sys_signal_null
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 1
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7340): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7340): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7340): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7340): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7316): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7316): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7282): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7282): MCCMNC not supported: null
D/libc-netbsd(  328): res_queryN name = clients3.google.com succeed
D/QRemote ( 7340): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7340): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7340): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7340): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7340): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LGDataListener(  328): argv[0]=dsqncommand
D/LGDataListener(  328): argv[1]=wlan0
D/LGDataListener(  328): argv[2]=1
D/LGDataListener(  328): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
W/dhcpcd  ( 7415): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7415): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7415): version 5.5.6 starting
,E/dhcpcd  ( 7415): get_duid: m
D/dhcpcd  ( 7415): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7415): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 22:30:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452292241345], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452292241323]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1832): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1450): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1832):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1450): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1450): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7415): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7415): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7415): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7415): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 7415): wlan0: sending REQUEST (xid 0xe92be4e5), next in 3.23 seconds
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7441 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7441): onCreate
,W/AppUp4:DB( 7441):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7441):  setFingerPrint start
I/AppUp4:DB( 7441):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7441):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7441):  SDK version = 21
I/AppUp4:DB( 7441):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7441): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7441): onReceive
D/LgDataFeature( 7441): LgDataFeature() Constructor: none
D/LgDataFeature( 7441): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7441): Context : android.app.ReceiverRestrictedContext@3f42ebd7
D/AppUp4:CustFacade( 7441): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7441): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7441): begin check event
I/AppUp4:CustModeStarterReceiver( 7441): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7441): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7441): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7441): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7441): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6842:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6842/cgroup.procs: No such file or directory
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3412): DownloadService onCreate
,I/DownloadManager( 3412): in removeSpuriousFiles
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@39fd88cb on behalf of 3412
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
,I/DownloadManager( 3412): in trimDatabase
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@8a348a8 on behalf of 3412
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7471 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3412): DownloadService onStartCommand
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@25d9e6a7 on behalf of 3412
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3412): processing inserted download 1
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3412): processing inserted download 4
V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
V/DownloadManager( 3412): processing inserted download 10
V/DownloadManager( 3412): processing inserted download 16
V/DownloadManager( 3412): processing inserted download 17
V/DownloadManager( 3412): processing inserted download 18
V/DownloadManager( 3412): processing inserted download 21
,V/DownloadManager( 3412): DownloadService onDestroy
W/ResourcesManager( 7471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7471): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 83274(3MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.479ms total 77.192ms
,I/LGEmail ( 7471): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7471): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7471): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7471): LgDataFeature() Constructor: none
D/LgDataFeature( 7471): LgDataFeature() Constructor Done, null
,D/eas_req ( 7471): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7501 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 7471): JNI_OnLoad()
I/HubEmail( 7471): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7471): registerNatives()
I/HubEmail( 7471): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7471): registerNativeMethods()
I/HubEmail( 7471): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7471): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1037): Killing 6881:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
,D/ConnectivityManager.CallbackHandler( 1450): CM callback handler got msg 524295
I/dhcpcd  ( 7415): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7415): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7415): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7415): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7415): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7415): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7415): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7415): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7415): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6881/cgroup.procs: No such file or directory
W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3353): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3353): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7539 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7571 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6936:com.lge.eula/1000 (adj 15): empty #17
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6936/cgroup.procs: No such file or directory
,D/WeatherAncestor( 6677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:43
,D/Weather.Utils( 6677): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 6677): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6677): 2 : This is isUpdating : false
D/WeatherAncestor( 6677): connectivity changed - connection : true
D/WeatherService( 6677): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@343c27ad
D/ForecastDataCache( 6677): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6677): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6677): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:43
D/libc-netbsd(  328): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7589 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6907:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,V/FormManager( 7501): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7501): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6907/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6969:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6969/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7589): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7589): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7589): Loading: webviewchromium
,I/LibraryLoader( 7589): Time to load native libraries: 4 ms (timestamps 2105-2109)
I/LibraryLoader( 7589): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7589): Binding Chromium to main looper Looper (main, tid 1) {184b43de}
I/LibraryLoader( 7589): Expected native library version number "",actual native library version number ""
I/chromium( 7589): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7589): Initializing chromium process, renderers=0
,W/art     ( 7589): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  332): registerClient() client 0xb14fdca0, uid 10093
,W/AudioManagerAndroid( 7589): Requires BLUETOOTH permission
W/chromium( 7589): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7589): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7589): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7589): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7589): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7589): Build Date: 12/12/14 금
I/Adreno-EGL( 7589): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7589): Remote Branch: 
I/Adreno-EGL( 7589): Local Patches: 
I/Adreno-EGL( 7589): Reconstruct Branch: 
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 7589): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7654 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 7009:com.lge.clock/u0a10 (adj 15): empty #17
,I/art     (  359): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 11.349ms
I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 9.304ms
,I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.807ms
W/libprocessgroup( 1037): failed to open /acct/uid_10010/pid_7009/cgroup.procs: No such file or directory
,W/ResourcesManager( 7654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7441): onReceive
,D/AppUp4:CustFacade( 7441): Context : android.app.ReceiverRestrictedContext@3f42ebd7
D/AppUp4:CustFacade( 7441): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7441): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7441): begin check event
I/AppUp4:CustModeStarterReceiver( 7441): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/art     ( 2050): Explicit concurrent mark sweep GC freed 42465(2MB) AllocSpace objects, 8(1047KB) LOS objects, 51% free, 30MB/62MB, paused 918us total 38.128ms
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3412): DownloadService onCreate
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3412): in removeSpuriousFiles
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@32aa26fd on behalf of 3412
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
,I/DownloadManager( 3412): in trimDatabase
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): DownloadService onStartCommand
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@377c84c0 on behalf of 3412
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@3cf735f9 on behalf of 3412
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3412): processing inserted download 1
V/DownloadManager( 3412): processing inserted download 4
,V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
V/DownloadManager( 3412): processing inserted download 10
V/DownloadManager( 3412): processing inserted download 16
V/DownloadManager( 3412): processing inserted download 17
,I/GLSActivity( 2050): [ac] getting account id
I/LgeMiscReceiver( 3353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3353): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3353): networkInfo.isConnected() = false
W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3412): processing inserted download 18
V/DownloadManager( 3412): processing inserted download 21
,I/GLSUser ( 2050): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/WeatherAncestor( 6677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:44
I/GLSUser ( 2050): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2050): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/Weather.Utils( 6677): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6677): 2 : All the weather widget is gone.
I/GLSUser ( 2050): [GLSUser] Extracting token using key: Auth
D/UpdateThreadPoolManager( 6677): 2 : This is isUpdating : false
W/GLSActivity( 2050): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WeatherAncestor( 6677): connectivity changed - connection : true
D/WeatherService( 6677): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@343c27ad
V/DownloadManager( 3412): DownloadService onDestroy
D/ForecastDataCache( 6677): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6677): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6677): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:44
V/GLSActivity( 2050): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
V/FormManager( 7501): There are no updated forms. The schedule will be deleted.
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/Kids    ( 2347): [AccountUtils] Account not ready
W/Kids    ( 2347): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2347): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2347): 	at java.lang.Thread.run(Thread.java:818)
D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7501): Alarm would be updated, because LastCheckTime has been updated.
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{254b039f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7441): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7441): onReceive
,D/AppUp4:CustFacade( 7441): Context : android.app.ReceiverRestrictedContext@3f42ebd7
D/AppUp4:CustFacade( 7441): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7441): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7441): begin check event
I/AppUp4:CustModeStarterReceiver( 7441): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3412): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2050): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2050): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2050): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2050): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3412): DownloadService onCreate
V/GLSActivity( 2050): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/DownloadManager( 3412): in removeSpuriousFiles
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@254b039f on behalf of 3412
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3412): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3412): in trimDatabase
V/DownloadManager( 3412): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@28052cec on behalf of 3412
V/DownloadManager( 3412): DownloadService onStartCommand
V/DownloadManager( 3412): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/LgeMiscReceiver( 3353): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3353): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3353): networkInfo.isConnected() = true
D/PhoneState( 3353): setPdpRejectCasuse : false
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3412): created cursor android.database.sqlite.SQLiteCursor@2ee63abb on behalf of 3412
D/WeatherAncestor( 6677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:44
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3412): processing inserted download 1
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3412): processing inserted download 4
V/DownloadManager( 3412): processing inserted download 7
V/DownloadManager( 3412): processing inserted download 8
V/DownloadManager( 3412): processing inserted download 9
V/DownloadManager( 3412): processing inserted download 10
V/DownloadManager( 3412): processing inserted download 16
V/DownloadManager( 3412): processing inserted download 17
V/DownloadManager( 3412): processing inserted download 18
D/LgeQuickCoverNLService( 1402): onNotificationPosted
V/DownloadManager( 3412): processing inserted download 21
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
W/Settings( 7471): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
W/Kids    ( 2347): [AccountUtils] Account not ready
W/Kids    ( 2347): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2347): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2347): 	at java.lang.Thread.run(Thread.java:818)
D/Weather.Utils( 6677): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6677): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6677): 2 : This is isUpdating : false
D/WeatherAncestor( 6677): connectivity changed - connection : true
D/WeatherService( 6677): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@343c27ad
V/DownloadManager( 3412): DownloadService onDestroy
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/ForecastDataCache( 6677): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6677): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6677): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:30:44
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{254b039f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7501): There are no updated forms. The schedule will be deleted.
D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7501): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2050): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2050): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2050): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2050): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2050): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2347): [AccountUtils] Account not ready
W/Kids    ( 2347): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2347): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2347): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2347): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2347): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2347): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{254b039f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6811): Internal timer expired: 4
D/UEI.SmartControl( 6811): unbind internal service
,D/serial_port( 6811): close(fd = 24)
,I/UEI.SmartControl( 6811): Serial port is closed.
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  328): res_queryN name = www.google.com succeed
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  328): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7196): Test app app.js loaded
I/jxcore-log( 7196): 
,I/chromium( 7196): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7196): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7196): 
,I/chromium( 7196): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7196): --= Surplus to requirements =--
I/jxcore-log( 7196): 
I/jxcore-log( 7196): ****TEST TOOK:  ms ****
I/jxcore-log( 7196): 
I/jxcore-log( 7196): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7196): 
,D/AndroidRuntime( 7733): 
D/AndroidRuntime( 7733): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7733): CheckJNI is OFF
D/AndroidRuntime( 7733): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 7196:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1037): WIN DEATH: Window{82a710d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{82a710d u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{d8296af com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{280e41ae u0 com.test.thalitest/.MainActivity t4}
,W/ActivityManager( 1037): Spurious death for ProcessRecord{326ccb54 7196:com.test.thalitest/u0a311}, curProc for 7196: null
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{280e41ae u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{280e41ae u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1921): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1921): topRunningActivity=ActivityInfo{18aa1267 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2013): [Launcher.java:5338:onStart()]onStart
,D/SplitWindowPolicy( 1921): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1921): topRunningActivity=ActivityInfo{34af6814 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2013): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1450): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1796): Ignoring removeGeofence because network location is disabled.
,E/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 1976): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/art     ( 4563): Explicit concurrent mark sweep GC freed 16123(916KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 461us total 60.770ms
D/LIA_MrGDBLogger_PackageInfoDetector( 3746): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4503): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4503): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4503): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4503): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4503): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4503): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4503): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4503): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4503): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4503): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2013): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2013): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PostponalbeReceiver( 6592): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/SplitUIManager( 1849): split_name #11 / not available #0
D/SplitUIService( 1849): removed split : 
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7757 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1886): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2013): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3746): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]LGActivityUtil( 2013): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1450): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2013): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2013): [Launcher.java:1114:onPause()]onPause
D/administrator( 1037): Handling package changes for user 0
I/[LGHome]GBoardWebView( 2013): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3746): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1886): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3746): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2013): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2013): , create_time: 1430558575574
I/GBoardWebViewUtils( 2013): , expire_time: 0
I/GBoardWebViewUtils( 2013): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2013): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2013): , display: false
I/GBoardWebViewUtils( 2013): , animation: false }
I/GBoardWebViewUtils( 2013): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2013): , create_time: 1430558575600
I/GBoardWebViewUtils( 2013): , expire_time: 0
I/GBoardWebViewUtils( 2013): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2013): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2013): , display: false
I/GBoardWebViewUtils( 2013): , animation: false }
I/GBoardWebViewUtils( 2013): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2013): , create_time: 1452175675684
I/GBoardWebViewUtils( 2013): , expire_time: 0
I/GBoardWebViewUtils( 2013): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2013): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2013): , display: false
I/GBoardWebViewUtils( 2013): , animation: false }
D/SplitUIManager( 1849): split_name #11 / not available #0
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/SplitUIService( 1849): split app #11
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1450): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1450): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/WallpaperManager( 2013): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d8359fe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/AppUp4:PreloadHelper( 7441): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2013): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2013): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/LockScreenSettings( 7757): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7778 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3797): [BTUI] [-] updateMediaPlayerInfo
,I/[LGHome]EVENT( 2013): [Launcher.java:5349:onStop()]onStop
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1450): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1450): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1450):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1450): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/ResourcesManager( 7778): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7778): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7778): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7778): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7778): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2013): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/SystemConfig( 7778): BUILD Country: EU
I/SystemConfig( 7778): BUILD Operator: OPEN
,I/[LGHome]Launcher.Model( 2013): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{3017df49 u0 com.lge.launcher2/.Launcher t3} time:275432
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2013): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2013): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2013): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2013): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2593): onStartCommand(). Type : 8
D/[Concierge]Service( 2593): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2593): Update widget ID : 11
D/[Concierge]WidgetView( 2013): change position of spinner
I/art     ( 1037): Explicit concurrent mark sweep GC freed 36652(2MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.149ms total 333.759ms
I/art     ( 1037): WaitForGcToComplete blocked for 168.095ms for cause Explicit
I/[Concierge]WidgetView( 2013): initWebView(). Time : 1452292247435
D/[Concierge]Service( 2593): onStartCommand(). Type : 0
I/[Concierge]WebView( 2013): Return exist ConciergeWebView. Reuse : 89013361
D/[Concierge]WidgetView( 2013): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2013): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2013): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@27484c7f
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2013): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2013): isWidgetUpdateSkippable ? true
,D/[Concierge]WidgetBroadcastReceiver( 2013): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1037): Killing 7030:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/art     ( 1037): Explicit concurrent mark sweep GC freed 5373(334KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.625ms total 70.549ms
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1037): failed to open /acct/uid_10014/pid_7030/cgroup.procs: No such file or directory
,W/[Concierge]WidgetView( 2013): Widget kill message received. Destory myself. My : 1452292000030, New one : 1452292247435
D/[Concierge]WidgetView( 2013): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2013): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1450): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1450): createShortcutInfo...
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/AndroidRuntime( 7733): Shutting down VM
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1450): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1450): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,D/KeyguardModel( 1450): createShortcutInfo...
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1450): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1450): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1450): createShortcutInfo...
,D/VoicemailCleanupService( 2364): Cleaning up data for package: com.test.thalitest
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/PackageChangeReceiver( 7471): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/SystemConfig( 7778): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7778): existFile = false
I/SystemConfig( 7778): canReadFile = false
I/SystemConfig( 7778): systemFeature RCS result false
D/SystemConfig( 7778): refreshRcsSupport() :false
D/KeyguardModel( 1450): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1450): createShortcutInfo...
I/[LgeWidgetLib]LgeAppWidgetHostView( 2013): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2013): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2013): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2013): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2013): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7801 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/KeyguardModel( 1450): handleShortcutListChanged...
D/KeyguardModel( 1450): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1450): createShortcutInfo...
D/KeyguardModel( 1450): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1450): createShortcutInfo...
,W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1450): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1450): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1450): createShortcutInfo...
W/ResourceType( 1450): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1450): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/Timeline( 2013): Timeline: Activity_idle id: android.os.BinderProxy@6503b08 time:275693
D/KeyguardModel( 1450): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1450): createShortcutInfo...
I/ActivityManager( 1037): Killing 6989:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6989/cgroup.procs: No such file or directory
D/KeyguardModel( 1450): handleShortcutListChanged...
W/ResourcesManager( 7801): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7801): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7801): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7801): Total System Memory = 2995761152
,D/SystemHelper( 7801): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1037): Killing 7090:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/chromium( 2013): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2013): onReloaded()
,D/LIA_Service_NativeEventReceiver( 1976): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 1976): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_7090/cgroup.procs: No such file or directory
I/GBoardWebViewClient( 2013): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_LIAService( 1976): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3746): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/PostponalbeReceiver( 6592): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3746): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7825 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/ActionManagerService( 1886): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3746): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3746): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1886): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3746): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3746): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3746): getSize() : size - 0
V/BoardContentProvider( 3746): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_Tips_SmartTipsActionManager( 3746): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2013): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2013): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2013): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2013): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2013): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2013): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 7825): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 7825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7825): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 7825): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7825): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7825): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7825): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7825): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7825): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7825): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7825): 	at com.android.internal.os.ZygoteInit.main(Zygot,eInit.java:704)
E/LifetrackerProvider2( 7825): Unable to open database for writing.
E/LifetrackerProvider2( 7825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 7825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 7825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 7825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 7825): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 7825): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 7825): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 7825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 7825): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 7825): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 7825): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 7825): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 7825): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 7825): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/ActivityThread( 7825): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7825): No ProfileInfo entries
I/LG Account v2.2( 7825): isEnabled: false
I/Feature ( 7825): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7825): [Lifetracker]Country: EU
I/Feature ( 7825): [Lifetracker]Operator: OPEN
I/Feature ( 7825): [Lifetracker]Ranking support: false
I/Feature ( 7825): [Lifetracker]Comfort support: false
I/Feature ( 7825): [Lifetracker]Accessory: true
I/Feature ( 7825): [Lifetracker]Health device: true
I/Feature ( 7825): [Lifetracker]Extra Pedometer: false
I/Feature ( 7825): [Lifetracker]Blood glucose device: false
I/Feature ( 7825): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 7825): [onReceive] Action=android.intent.action.PACKAGE_REMOVED

```
