#### Test 564496606be5677_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/AndroidRuntime( 7074): 
D/AndroidRuntime( 7074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7074): CheckJNI is OFF
D/AndroidRuntime( 7074): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1981): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3e4d4f9 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3e4d4f9 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7094 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7074): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1872): Display #0 changed.
D/SplitWindowPolicy( 1981): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1981): topRunningActivity=ActivityInfo{f8831e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1981): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1981): topRunningActivity=ActivityInfo{28f727ff co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7094): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7094): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7094): Loading: webviewchromium
,I/LibraryLoader( 7094): Time to load native libraries: 11 ms (timestamps 9263-9274)
I/LibraryLoader( 7094): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7094): Binding Chromium to main looper Looper (main, tid 1) {5d1da4e}
,I/LibraryLoader( 7094): Expected native library version number "",actual native library version number ""
I/chromium( 7094): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7094): Initializing chromium process, renderers=0
,W/art     ( 7094): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  317): registerClient() client 0xb1184c60, uid 10311
,W/chromium( 7094): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7094): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7094): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@110ee1bb:true
I/Adreno-EGL( 7094): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7094): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7094): Build Date: 12/12/14 금
I/Adreno-EGL( 7094): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7094): Remote Branch: 
I/Adreno-EGL( 7094): Local Patches: 
I/Adreno-EGL( 7094): Reconstruct Branch: 
,W/chromium( 7094): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7094): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7094): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7094): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7094): CordovaWebView is running on device made by: LGE
,W/art     ( 7094): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7094): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7094): Render dirty regions requested: true
I/OpenGLRenderer( 7094): Initialized EGL, version 1.4
D/OpenGLRenderer( 7094): Enabling debug mode 0
,D/Atlas   ( 7094): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{12f016dd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7094): LgDataFeature() Constructor: none
,D/LgDataFeature( 7094): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@317c629b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1474): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +627ms (total +721ms)
I/Timeline( 7094): Timeline: Activity_idle id: android.os.BinderProxy@d8f72fe time:309749
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{12e8bc3e u0 com.test.thalitest/.MainActivity t4} time:309751
,D/JsMessageQueue( 7094): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7094): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7094): 
,I/chromium( 7094): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7094): 
,D/jxcore_app_log( 7094): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
I/chromium( 7094): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7094): Initializing JXcore engine
W/jxcore-log( 7094): JXcore engine is ready
,W/Thread-819( 7155): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10699]" dev="sockfs" ino=10699 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-819( 7155): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-819( 7155): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8627]" dev="sockfs" ino=8627 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-819( 7155): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-819( 7155): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33095]" dev="sockfs" ino=33095 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 7094): Starting JXcore engine
W/jxcore-log( 7094): Platform android
W/jxcore-log( 7094): 
W/jxcore-log( 7094): Process ARCH arm
W/jxcore-log( 7094): 
,I/art     ( 7094): Background sticky concurrent mark sweep GC freed 137458(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.195ms total 193.229ms
,I/jxcore-log( 7094): JXcore Cordova bridge is ready!
I/jxcore-log( 7094): 
W/jxcore-log( 7094): JXcore engine is started
,I/jxcore-log( 7094): Toggling radios to true
I/jxcore-log( 7094): 
,D/BluetoothAdapter( 7094): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7094, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7094, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1038): disconnect pid=7094, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1038): reconnect pid=7094, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7094): Radios toggled
I/jxcore-log( 7094): 
I/jxcore-log( 7094): My device name is: LGE-LG-D855
I/jxcore-log( 7094): 
E/WifiNative: ( 1038): [312,935,231 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
D/Tethering( 1038): InitialState.processMessage what=4
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Clearing all IP addresses on wlan0
V/NativeCrypto( 2144): Read error: ssl=0xaa6d0000: I/O error during system call, Connection timed out
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7169 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [313,024,644 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaa6d0000: I/O error during system call, Broken pipe
,D/WifiHS20( 1038): hidePasspointNotification off =false
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/WfdStateTracker( 1981): handleWifiStateChangedEvent: 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1038): RECONNECT: returned true
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=313047
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=313047
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  313): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): stop dsqn bin
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=313087  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=313087  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=313093  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor Netw,orkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1038): Removing idletimer
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=313103  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
,W/ResourcesManager( 7169): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7169): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7169): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7169): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7169): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7169): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1038): StoppedState
,D/DhcpStateMachine( 1038): StoppedState{ when=-191ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7169): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7169): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7169): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7169): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7169): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7169): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7202 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6592:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=595749726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{174b319e type 0 when 1453288746870 android} when 1453288746870
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6592/cgroup.procs: No such file or directory
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1256747f type 2 when 313296 com.google.android.gms} when 313296
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7169): LgDataFeature() Constructor: none
D/LgDataFeature( 7169): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7223 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1038): Killing 6089:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6089/cgroup.procs: No such file or directory
,W/ResourcesManager( 7223): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7223): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7223): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7223): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7223): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7223): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7223): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7223): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7223): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7223): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/QRemote ( 7223): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:249254] from screen [on:0 period:1589801626]
V/QRemote ( 7223): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=595749726 [*alarm*], flags=0x0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7223): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LgDataFeature( 7223): LgDataFeature() Constructor: none
D/LgDataFeature( 7223): LgDataFeature() Constructor Done, null
,V/SoundPool( 7223): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7223): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7223): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7223): doLoad: loading sample sampleID=1
I/QRemote ( 7223): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6687): QS Service created
D/QRemote ( 7223): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/SoundPool( 7223): Start decode
V/MediaPlayer[Native]( 7223): decode(31, 10857164, 17813)
V/MediaPlayerService(  317): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  317): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  317): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  317): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  317): player type = 3
V/AwesomePlayer(  317): AwesomePlayer create()
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): setAudioSink() 
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb14325c0, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/Utils   (  317): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  317): setDataSource_l dataSource
V/LGParserOSAL(  317): SniffLGParser start
V/LGParserOSAL(  317): MainType:5, SubType=0
V/LGParserOSAL(  317): #### check Mime : application/ogg
V/LGParserOSAL(  317): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  317): Use LGExtractor :application/ogg 
,E/QRemote ( 7223): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7223): Create singleton instance
I/UEI.SmartControl( 6687): Service initServices...
D/UEI.SmartControl( 6687): QS start get config
,V/LGParserOSAL(  317): supported mime: application/ogg
,V/AwesomePlayer(  317): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  317): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  317): mBitrate = -1 bits/sec
V/AwesomePlayer(  317): AudioTrack Setting
V/AwesomePlayer(  317): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  317): setAudioSource() 
V/MediaPlayerService(  317): prepare
V/AwesomePlayer(  317): prepareAsync_l() 
V/MediaPlayerService(  317): wait for prepare
V/AwesomePlayer(  317): onPrepareAsyncEvent() 
V/AwesomePlayer(  317): initAudioDecoder() 
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AwesomePlayer(  317): getUseOffload() = 0 
V/OMXCodec(  317): OMXCodec::Create
V/OMXCodec(  317): findMatchingCodecs()
V/OMXCodec(  317): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  317): matchingCodecs.size()=1
V/OMXCodec(  317): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  317): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  317): LG Codec Adapter start
V/OMXCodec(  317): OMXCodec Createtor
V/OMXCodec(  317): setComponentRole
V/OMXCodec(  317): configureCodec protected=0
V/LGCodecAdapter(  317): called getLGCodecSpecificData
V/LGCodecOSAL(  317): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMSG
V/LGCodecOSAL(  317): Not support LGCodec
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  317): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  317): Could not offload audio decode, try pcm offload
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  317): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  317): init()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  317): allocateBuffers
V/OMXCodec(  317): allocateBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ce0 on output port
V/OMXCodec(  317): in,it() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  317): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  317): finishAsyncPrepare_l() 
V/AudioCache(  317): notify(0xb14325c0, 5, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): notify(0xb14325c0, 1, 0, 0)
V/AudioCache(  317): prepared
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): start
V/AwesomePlayer(  317): play_l() 
V/AwesomePlayer(  317): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  317): createAudioPlayer_l
V/AwesomePlayer(  317): seekAudioIfNecessary_l() 
V/AwesomePlayer(  317): startAudioPlayer_l() 
D/AudioPlayer(  317): start of Playback, useOffload 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  317): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975584
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975744
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977824
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  317): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb153a2e0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  317): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  317): notify(0xb14325c0, 6, 0, 0)
V/AudioCache(  317): ignored
V/MediaPlayerService(  317): wait for playback complete
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf404000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf405000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf406000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf407000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf408000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf409000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40a000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40b000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40c000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40d000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40e000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf40f000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf410000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf411000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf412000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf413000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf414000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf415000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf416000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf417000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf418000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf419000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41a000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41b000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41c000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41d000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41e000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf41f000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf420000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf421000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf422000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf423000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf424000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf425000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf426000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf427000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf428000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf429000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42a000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42b000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42c000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42d000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42e000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf42f000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf430000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf431000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf432000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf433000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf434000, 0xb57fc000, 4096)
V/AudioCache(  317): write(0xb57fc000, 4096)
V/AudioCache(  317): memcpy(0xaf435000, 0xb57fc000, 4096)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  317): postAudioEOS() 
V/AudioCache(  317): write(0xb57fc000, 280)
V/AudioCache(  317): memcpy(0xaf436000, 0xb57fc000, 280)
V/AwesomePlayer(  317): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  317): onStreamDone
V/AwesomePlayer(  317): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  317): notify(0xb14325c0, 2, 0, 0)
V/AudioCache(  317): playback complete
V/AwesomePlayer(  317): pause_l() 
V/AudioCache(  317): notify(0xb14325c0, 7, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  317): Pause Playback at 1068125
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb14325c0, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/AudioPlayer(  317): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb153a2e0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  317): AudioPlayer releasing audio source
D/AudioPlayer(  317): AudioPlayer done releasing audio source
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): ~AwesomePlayer call
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
,V/SoundPool( 7223): close(31)
,V/SoundPool( 7223): pointer = 0x9ffc0000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7223): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:829
I/UEI.SmartControl( 6687): Supports setup maps: true
,D/UEI.SmartControl( 6687): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6687): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6687): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6687): ### init IR Blaster...
D/serial_port( 6687): Configuring serial port
E/UEI.SmartControl( 6687): UEIBLaster setting for 616
I/UEI.SmartControl( 6687): Setting serial record hearder size = 2
I/UEI.SmartControl( 6687): configuring settings for MAXQ616
I/UEI.SmartControl( 6687): Get version...
D/UEI.SmartControl( 6687): serial port data available: 21
,D/UEI.SmartControl( 6687): MAXQ616 A2-X4 software.,
,I/UEI.SmartControl( 6687): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6687): QS saving settings...
D/UEI.SmartControl( 6687): IR Blaster version: 25672567
,D/UEI.SmartControl( 6687): serial port data available: 4,
,I/UEI.SmartControl( 6687): Device manager: loading config....
,D/UEI.SmartControl( 6687): ----------- loading internal config...
W/ContextImpl( 6687): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6687): Services init done
D/UEI.SmartControl( 6687): QS Service init finished
D/UEI.SmartControl( 6687): QS Service version name: 2.1.91
D/UEI.SmartControl( 6687): QS Service version code: 201091
D/UEI.SmartControl( 6687): Service requested: Control
D/UEI.SmartControl( 6687): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6687): Loading SETTINGS...
I/QRemote ( 7223): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6687): ------ IControl API: 11
D/UEI.SmartControl( 6687): File observer start...
E/UEI.SmartControl( 6687): IR Port is disabled: false
D/UEI.SmartControl( 6687): Starting file observer...
I/UEI.SmartControl( 6687): Registering callback...
I/UEI.SmartControl( 6687): ------ IControl API: 19
I/UEI.SmartControl( 6687): Registering Services Ready callback...
D/UEI.SmartControl( 6687): Internal service binding...
D/UEI.SmartControl( 6687): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6687): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6687): -----service ready thread exits
,I/QRemote ( 7223): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7223): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,D/QRemote ( 7223): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7223): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7223): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6687): ------ IControl API: 8
D/QRemote ( 7223): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7223): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7223): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7223): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 7223): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7223): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7223): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7223): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{ad8e402 type 2 when 314614 com.google.android.gms} when 314614
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7223): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7223): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453288748208]
D/QRemote ( 7223): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6109:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7223): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6109/cgroup.procs: No such file or directory
,V/QRemote ( 7223): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7223): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7223): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
,I/wpa_supplicant( 2698): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=315117  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=315136  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{f5de113 type 2 when 315658 com.google.android.gms} when 315658
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=false
I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7311 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7311): onCreate
,W/AppUp4:DB( 7311):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7311):  setFingerPrint start
I/AppUp4:DB( 7311):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7311):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7311):  SDK version = 21
I/AppUp4:DB( 7311):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7311): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7311): onReceive
D/LgDataFeature( 7311): LgDataFeature() Constructor: none
D/LgDataFeature( 7311): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@359d8c7c
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7311): begin check event
I/AppUp4:CustModeStarterReceiver( 7311): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7311): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7311): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7311): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7311): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6517:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6517/cgroup.procs: No such file or directory
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 6628): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7333 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 22.387ms
,I/HubEmail( 6628): JNI_OnLoad()
I/HubEmail( 6628): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6628): registerNatives()
I/HubEmail( 6628): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6628): registerNativeMethods()
I/HubEmail( 6628): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6628): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.321ms
,W/Settings( 6628): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 306us total 12.308ms
I/LgeMiscReceiver( 3375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3375): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3375): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7358 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7333): Network not available. Please check & try again.
,V/FormManager( 7333): Network unavailable.
V/FormManager( 7333): Network unavailable.
,I/ActivityManager( 1038): Killing 6656:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6656/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7377 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6722:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7094): 
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6722/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7394 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6760:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6760/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,E/WifiStateMachine( 1038):  DisconnectedState ASSOCIATION_REJECTION_EVENT 27 1 c0:ff:d4:d3:aa:48 blacklist=false rt=317326
E/WifiStateMachine( 1038):  ConnectModeState ASSOCIATION_REJECTION_EVENT 27 1 c0:ff:d4:d3:aa:48 blacklist=false rt=317327
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=317327  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=317330  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 7394): Almond Protected OAT,
,D/WeatherApplication( 7394): removeAccount
,D/WeatherApplication( 7394): Account.length = 0
E/WeatherApplication( 7394): OPERATOR:OPEN
D/WeatherAncestor( 7394): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:19:10
D/Weather.Utils( 7394): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7394): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7394): 2 : This is isUpdating : false
D/WeatherAncestor( 7394): connectivity changed - connection : true
D/WeatherService( 7394): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7394): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7394): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7394): 2 : Cache is not up-to-date, count: 0
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=317427  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=317428  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/Weather_cast( 7394): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7394): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:19:11
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7415 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6812:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6812/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2dd0e481 type 2 when 317708 com.google.android.gms} when 317708
,I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7094): 
,I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7094): 
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7415): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7415): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7415): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7415): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7094): 
,I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7094): 
,I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7094): 
I/jxcore-log( 7094): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7094): 
,E/WifiStateMachine( 1038):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/WebViewFactory( 7415): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 58339(2MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.441ms total 107.099ms
,I/LibraryLoader( 7415): Loading: webviewchromium
I/LibraryLoader( 7415): Time to load native libraries: 2 ms (timestamps 8098-8100)
I/LibraryLoader( 7415): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7415): Binding Chromium to main looper Looper (main, tid 1) {1d58fbf1}
I/LibraryLoader( 7415): Expected native library version number "",actual native library version number ""
I/chromium( 7415): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7415): Initializing chromium process, renderers=0
W/art     ( 7415): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7415): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7415): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 7415): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,V/AudioPolicyService(  317): registerClient() client 0xb1523320, uid 10093
W/AudioManagerAndroid( 7415): Requires BLUETOOTH permission
I/Adreno-EGL( 7415): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7415): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7415): Build Date: 12/12/14 금
I/Adreno-EGL( 7415): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7415): Remote Branch: 
I/Adreno-EGL( 7415): Local Patches: 
I/Adreno-EGL( 7415): Reconstruct Branch: 
,I/NSApplication( 7415): Starting up...
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 318180856654; DSPS: 10567041; Offset : -4311507325
I/ActivityManager( 1038): Killing 6855:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6855/cgroup.procs: No such file or directory
,I/iu.Environment( 2370): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2370): num queued entries: 0
I/iu.UploadsManager( 2370): num updated entries: 0
I/iu.SyncManager( 2370): NEXT; no task
D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7311): onReceive
,D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@359d8c7c
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7311): begin check event
,I/AppUp4:CustModeStarterReceiver( 7311): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 6628): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 6628): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3375): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3375): networkInfo.isConnected() = false
W/FormManager( 7333): Network not available. Please check & try again.
D/WeatherAncestor( 7394): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:19:12
,D/Weather.Utils( 7394): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7394): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7394): 2 : This is isUpdating : false
D/WeatherAncestor( 7394): connectivity changed - connection : true
D/WeatherService( 7394): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36754d5a
D/ForecastDataCache( 7394): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7394): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7394): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7394): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7394): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:19:12
V/FormManager( 7333): Network unavailable.
V/FormManager( 7333): Network unavailable.
,D/ChimeraCfgMgr( 2370): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
,D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
,I/wpa_supplicant( 2698): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=319476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=319491  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6687): Internal timer expired: 2
D/UEI.SmartControl( 6687): unbind internal service
,D/serial_port( 6687): close(fd = 24)
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
I/UEI.SmartControl( 6687): Serial port is closed.
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/jxcore-log( 7094): Test app app.js loaded
I/jxcore-log( 7094): 
,I/chromium( 7094): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7094): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7094): BLE advertisement is supported
I/jxcore-log( 7094): 
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState ASSOCIATION_REJECTION_EVENT 34 1 c0:ff:d4:d3:aa:48 blacklist=false rt=322031
E/WifiStateMachine( 1038):  ConnectModeState ASSOCIATION_REJECTION_EVENT 34 1 c0:ff:d4:d3:aa:48 blacklist=false rt=322031
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=322032  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=322047  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=322543  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=322575  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7202): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/GAV4    ( 7415): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 2698): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=324669  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=324698  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2698): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=325268  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=325269  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=325270
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=325270
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=325271
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=325271
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=325271
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=325272  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 2698): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=325329  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=325339  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=325340  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=325341
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=325341
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  313): Setting iface cfg
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
,E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=325431  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=325432  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=325434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7169): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7169): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7169): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=325446  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=325446  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=325447  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsControl( 7169): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : activeList=[]
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7169): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7169): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsControl( 7169): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3eae913 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3eae913 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1981): handleWifiStateChangedEvent: 1
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  313): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7555): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
W/dsqn    ( 7555): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7555): DSQN ssw
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7223): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
,D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7223): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7223): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7223): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7202): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7202): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7169): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7169): MCCMNC not supported: null
D/QRemote ( 7223): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7223): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7223): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7223): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7223): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7559): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7559): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7559): version 5.5.6 starting
,E/dhcpcd  ( 7559): get_duid: m
D/dhcpcd  ( 7559): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7559): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
,D/dhcpcd  ( 7559): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7559): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7559): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7559): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7559): wlan0: sending REQUEST (xid 0xedd7bb0), next in 3.34 seconds
,D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 20 Jan 2016 11:19:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453288759776], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453288759643]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
,D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
,D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524295
I/dhcpcd  ( 7559): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7559): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7559): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7559): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7559): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7559): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7559): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7559): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7559): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
,I/jxcore-log( 7094): --= Surplus to requirements =--
I/jxcore-log( 7094): 
I/jxcore-log( 7094): ****TEST TOOK:  ms ****
I/jxcore-log( 7094): 
I/jxcore-log( 7094): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7094): 
,D/AndroidRuntime( 7605): 
D/AndroidRuntime( 7605): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7605): CheckJNI is OFF
D/AndroidRuntime( 7605): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7094:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1038): Skipping PackageSetting{2da06a9d com.example.hello/10319} due to missing metadata
,I/WindowState( 1038): WIN DEATH: Window{12f016dd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{12f016dd u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{12e8bc3e u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{3fb8e90e 7094:com.test.thalitest/u0a311}, curProc for 7094: null
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{12e8bc3e u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1981): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{12e8bc3e u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1981): topRunningActivity=ActivityInfo{2da5e9cc co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1981): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1981): topRunningActivity=ActivityInfo{1ca8e415 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2093): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2093): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2051): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3760): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[LGHome]EVENT( 2093): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     ( 4605): Explicit concurrent mark sweep GC freed 15992(895KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 577us total 90.320ms
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7635 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1474): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1925): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3760): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1474): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/PostponalbeReceiver( 6561): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4557): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4557): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4557): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 4557): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4557): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4557): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4557): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4557): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4557): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4557): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/NetworkMonitor( 5445): type=WIFI subType= reason=null isConnected=true
,I/[LGHome]LGActivityUtil( 2093): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2093): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2093): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1925): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3760): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3760): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2093): , create_time: 1430558575574
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2093): , create_time: 1430558575600
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
I/GBoardWebViewUtils( 2093): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2093): , create_time: 1452774039338
I/GBoardWebViewUtils( 2093): , expire_time: 0
I/GBoardWebViewUtils( 2093): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2093): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2093): , display: false
I/GBoardWebViewUtils( 2093): , animation: false }
D/WallpaperManager( 2093): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/AppUp4:PreloadHelper( 7311): added Exclude : com.test.thalitest
,W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@317c629b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1889): split_name #11 / not available #0
D/SplitUIService( 1889): removed split : 
I/[LGHome]EVENT( 2093): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2093): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/LockScreenSettings( 7635): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7658 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
I/art     ( 1038): Explicit concurrent mark sweep GC freed 63856(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.470ms total 227.956ms
D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1474): createShortcutInfo...
I/art     ( 1038): WaitForGcToComplete blocked for 105.348ms for cause Explicit
,W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3841): [BTUI] [-] updateMediaPlayerInfo
,D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/administrator( 1038): Handling package changes for user 0
D/SplitUIManager( 1889): split_name #11 / not available #0
I/SplitUIService( 1889): split app #11
D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
I/[LGHome]EVENT( 2093): [Launcher.java:5349:onStop()]onStop
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Killing 6836:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/ResourcesManager( 7658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7658): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1474): handleShortcutListChanged...
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6836/cgroup.procs: No such file or directory
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
D/PhoneStatusBar( 1474): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
,D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
D/KeyguardModel( 1474): handleShortcutListChanged...
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{43c66cc u0 com.lge.launcher2/.Launcher t3} time:328915
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2093): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2093): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/SystemConfig( 7658): BUILD Country: EU
I/SystemConfig( 7658): BUILD Operator: OPEN
,I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1038): Explicit concurrent mark sweep GC freed 9467(535KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.970ms total 192.862ms
I/[Concierge]WidgetView( 2093): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2612): onStartCommand(). Type : 8
,D/[Concierge]Service( 2612): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2612): Update widget ID : 11
D/[Concierge]WidgetView( 2093): change position of spinner
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2093): initWebView(). Time : 1453288762537
D/[Concierge]Service( 2612): onStartCommand(). Type : 0
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[Concierge]WebView( 2093): Return exist ConciergeWebView. Reuse : 235210062
D/[Concierge]WidgetView( 2093): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1038): Killing 6194:com.android.vending/u0a44 (adj 15): empty #17
,I/[LgeWidgetLib]ExtViewHost( 2093): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@247ea196
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2093): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2093): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2093): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/AndroidRuntime( 7605): Shutting down VM
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6194/cgroup.procs: No such file or directory
,W/[Concierge]WidgetView( 2093): Widget kill message received. Destory myself. My : 1453288461408, New one : 1453288762537
D/[Concierge]WidgetView( 2093): Unregister all receivers
,W/[Concierge]WidgetBroadcastReceiver( 2093): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/SystemConfig( 7658): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7658): existFile = false
I/SystemConfig( 7658): canReadFile = false
I/SystemConfig( 7658): systemFeature RCS result false
D/SystemConfig( 7658): refreshRcsSupport() :false
D/VoicemailCleanupService( 2189): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 6628): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 2093): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7681 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2093): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2093): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2093): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7681): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7681): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/Timeline( 2093): Timeline: Activity_idle id: android.os.BinderProxy@298cbc79 time:329210
I/AppConfig( 7681): Total System Memory = 2995761152
D/SystemHelper( 7681): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1038): Killing 6929:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/chromium( 2093): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LIA_Service_NativeEventReceiver( 2051): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,I/LIA_Service_PlatformUtil( 2051): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6929/cgroup.procs: No such file or directory
,D/LIA_Service_LIAService( 2051): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 6561): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardtInterface( 2093): onReloaded()
,I/GBoardWebViewClient( 2093): onPageFinished url:file:///android_asset/www/main.html
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7703 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BoardContentProvider( 3760): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
E/SQLiteLog( 4557): (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
V/BoardContentProvider( 3760): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
E/SQLiteDatabase( 4557): Error inserting f004=13 f005=7703 f002=1453288763051 f003=com.lge.lifetracker f006=10037
E/SQLiteDatabase( 4557): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 4557): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 4557): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 4557): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 4557): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 4557): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
E/SQLiteDatabase( 4557): 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
E/SQLiteDatabase( 4557): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
E/SQLiteDatabase( 4557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4557): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4557): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3760): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3760): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3760): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3760): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3760): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3760): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3760): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2093): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2093): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2093): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2093): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2093): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2093): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
