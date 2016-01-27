#### Test 564496604206eac_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257997513117; DSPS: 8594920; Offset : -4314682298
,D/AndroidRuntime( 7112): 
D/AndroidRuntime( 7112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7112): CheckJNI is OFF
D/AndroidRuntime( 7112): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1954): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{f891de6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{f891de6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  325): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7127 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7112): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1856): Display #0 changed.
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{1b954e5b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{31d446f8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7127): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7127): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7127): Loading: webviewchromium
I/LibraryLoader( 7127): Time to load native libraries: 3 ms (timestamps 2907-2910)
I/LibraryLoader( 7127): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7127): Binding Chromium to main looper Looper (main, tid 1) {1992e4cb}
,I/LibraryLoader( 7127): Expected native library version number "",actual native library version number ""
I/chromium( 7127): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7127): Initializing chromium process, renderers=0
W/art     ( 7127): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  307): registerClient() client 0xb1230740, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b4e5b40:true
W/chromium( 7127): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7127): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7127): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/Adreno-EGL( 7127): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7127): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7127): Build Date: 12/12/14 금
I/Adreno-EGL( 7127): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7127): Remote Branch: 
I/Adreno-EGL( 7127): Local Patches: 
I/Adreno-EGL( 7127): Reconstruct Branch: 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 24822(1090KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.819ms total 134.053ms
,W/chromium( 7127): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7127): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7127): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7127): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7127): CordovaWebView is running on device made by: LGE
,W/art     ( 7127): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7127): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{2a61ff27 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7127): Render dirty regions requested: true
I/OpenGLRenderer( 7127): Initialized EGL, version 1.4
D/OpenGLRenderer( 7127): Enabling debug mode 0
,D/Atlas   ( 7127): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{2e3c0d7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7127): LgDataFeature() Constructor: none
D/LgDataFeature( 7127): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1445): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27ef2af6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +669ms (total +749ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{2a61ff27 u0 com.test.thalitest/.MainActivity t4} time:263440
,I/Timeline( 7127): Timeline: Activity_idle id: android.os.BinderProxy@3c8a96bb time:263443
I/chromium( 7127): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7127): 
,D/JsMessageQueue( 7127): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7127): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7127): 
,D/jxcore_app_log( 7127): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435079040
,I/chromium( 7127): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  325): DFP En is all cleared set to be enabled
E/GBMv2   (  325): Set value is all cleared set the max
I/GBMv2   (  325): DFP Enabled. Ignore VFP set
W/jxcore-log( 7127): Initializing JXcore engine
W/jxcore-log( 7127): JXcore engine is ready
W/Thread-824( 7201): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7468]" dev="sockfs" ino=7468 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-824( 7201): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-824( 7201): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10047]" dev="sockfs" ino=10047 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-824( 7201): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-824( 7201): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34153]" dev="sockfs" ino=34153 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7127): Background sticky concurrent mark sweep GC freed 131929(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 2.211ms total 152.155ms
W/jxcore-log( 7127): Starting JXcore engine
W/jxcore-log( 7127): Platform android
W/jxcore-log( 7127): 
W/jxcore-log( 7127): Process ARCH arm
W/jxcore-log( 7127): 
I/jxcore-log( 7127): JXcore Cordova bridge is ready!
I/jxcore-log( 7127): 
W/jxcore-log( 7127): JXcore engine is started
I/jxcore-log( 7127): Toggling radios to true
I/jxcore-log( 7127): 
D/BluetoothAdapter( 7127): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7127, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7127, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7127, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [266,148,657 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7127, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7127): Radios toggled
I/jxcore-log( 7127): 
I/jxcore-log( 7127): My device name is: LGE-LG-D855
I/jxcore-log( 7127): 
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): InitialState.processMessage what=4
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/CommandListener(  301): Clearing all IP addresses on wlan0
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7211 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2116): Read error: ssl=0xaa6d6000: I/O error during system call, Connection timed out
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 2116): SSL shutdown failed: ssl=0xaa6d6000: I/O error during system call, Broken pipe
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1954): handleWifiStateChangedEvent: 0
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [266,304,021 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=266306
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=266307
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/CommandListener(  301): Clearing all IP addresses on wlan0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,D/libc-netbsd(  301): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=266330  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=266330  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=266338  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=266343  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, i,sConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Def,aultState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1856): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1856):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,W/ResourcesManager( 7211): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7211): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-135ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7211): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7211): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7211): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7247 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6525:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6525/cgroup.procs: No such file or directory
,I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
D/PCSuite ( 7247): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WifiController( 1037): battery changed pluggedType: 2
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1954): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1954): Battery Level Remaining: 100%
D/LEDHandler( 1954): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
W/MainApplication( 6927): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3818): Disconnected process message: 10, size: 0
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7211): LgDataFeature() Constructor: none
D/LgDataFeature( 7211): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7277 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6651:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6651/cgroup.procs: No such file or directory
,W/ResourcesManager( 7277): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7277): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7277): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7277): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7277): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7277): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7277): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7277): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7277): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7247): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7277): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7247): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7247): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7277): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7277): LgDataFeature() Constructor: none
D/LgDataFeature( 7277): LgDataFeature() Constructor Done, null
,V/SoundPool( 7277): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7277): load: fd=31, offset=10857164, length=17813, priority=1
V/SoundPool( 7277): create sampleID=1, fd=30, offset=17813 length=10857164
V/SoundPool( 7277): doLoad: loading sample sampleID=1
I/QRemote ( 7277): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7277): Start decode
V/MediaPlayer[Native]( 7277): decode(30, 10857164, 17813)
D/UEI.SmartControl( 6868): QS Service created
D/QRemote ( 7277): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/MediaPlayerService(  307): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  307): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  307): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  307): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  307): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  307): [getPlayerType:fd] nType = 3
,V/MediaPlayerService(  307): player type = 3
V/AwesomePlayer(  307): AwesomePlayer create()
V/AwesomePlayer(  307): reset_l() 
V/AwesomePlayer(  307): cancelPlayerEvents
V/AwesomePlayer(  307): setAudioSink() 
V/AwesomePlayer(  307): reset_l() 
V/AudioCache(  307): notify(0xb1163500, 8, 0, 0)
V/AudioCache(  307): ignored
V/AwesomePlayer(  307): cancelPlayerEvents
D/Utils   (  307): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  307): setDataSource_l dataSource
V/LGParserOSAL(  307): SniffLGParser start
V/LGParserOSAL(  307): MainType:5, SubType=0
V/LGParserOSAL(  307): #### check Mime : application/ogg
V/LGParserOSAL(  307): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  307): Use LGExtractor :application/ogg 
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6868): Service initServices...
D/UEI.SmartControl( 6868): QS start get config
V/LGMDMManager( 7277): Create singleton instance
,V/LGParserOSAL(  307): supported mime: application/ogg
V/AwesomePlayer(  307): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  307): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  307): mBitrate = -1 bits/sec
V/AwesomePlayer(  307): AudioTrack Setting
V/AwesomePlayer(  307): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  307): setAudioSource() 
V/MediaPlayerService(  307): prepare
V/AwesomePlayer(  307): prepareAsync_l() 
V/MediaPlayerService(  307): wait for prepare
,V/AwesomePlayer(  307): onPrepareAsyncEvent() 
V/AwesomePlayer(  307): initAudioDecoder() 
W/Utils   (  307): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  307): isOffloadSupported()
V/AudioPolicyManager(  307): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  307): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  307): isAudioPlaybackHookOn() false
V/AwesomePlayer(  307): getUseOffload() = 0 
V/OMXCodec(  307): OMXCodec::Create
V/OMXCodec(  307): findMatchingCodecs()
V/OMXCodec(  307): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  307): matchingCodecs.size()=1
V/OMXCodec(  307): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  307): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  307): LG Codec Adapter start
V/OMXCodec(  307): OMXCodec Createtor
V/OMXCodec(  307): setComponentRole
V/OMXCodec(  307): configureCodec protected=0
V/LGCodecAdapter(  307): called getLGCodecSpecificData
V/LGCodecOSAL(  307): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  307): Called LGconfigureCodecMETA
V/LGCodecOSAL(  307): Called LGconfigureCodecMSG
V/LGCodecOSAL(  307): Not support LGCodec
V/OMXCodec(  307): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  307): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  307): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  307): Could not offload audio decode, try pcm offload
W/Utils   (  307): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  307): isOffloadSupported()
V/AudioPolicyManager(  307): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  307): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  307): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  307): init()
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  307): allocateBuffers
V/OMXCodec(  307): allocateBuffersOnPort portIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a290 on input port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a380 on input port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a470 on input port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a600 on input port
V/OMXCodec(  307): allocateBuffersOnPort portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a6a0 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a880 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119aa10 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119ab50 on output port
V/OMXCodec(  307): init() mAsyncCompletion wait!!! 
V/OMXCodec(  307): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  307): init() mAsyncCompletion wait!!! 
V/OMXCodec(  307): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState m,State=3 , newState=4
V/OMXCodec(  307): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  307): finishAsyncPrepare_l() 
V/AudioCache(  307): notify(0xb1163500, 5, 0, 0)
V/AudioCache(  307): ignored
V/AudioCache(  307): notify(0xb1163500, 1, 0, 0)
V/AudioCache(  307): prepared
V/AudioCache(  307): wait - success
V/MediaPlayerService(  307): start
V/AwesomePlayer(  307): play_l() 
V/AwesomePlayer(  307): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  307): createAudioPlayer_l
V/AwesomePlayer(  307): seekAudioIfNecessary_l() 
V/AwesomePlayer(  307): startAudioPlayer_l() 
D/AudioPlayer(  307): start of Playback, useOffload 0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  307): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  307): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  307): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248288
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248768
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971249168
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971249488
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  307): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  307): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  307): allocateBuffersOnPort portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119aa10 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a880 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119a6a0 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] allocated buffer 0xb119ad80 on output port
V/OMXCodec(  307): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  307): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  307): notify(0xb1163500, 6, 0, 0)
V/AudioCache(  307): ignored
V/MediaPlayerService(  307): wait for playback complete
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab406000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab407000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab408000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab409000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40a000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40b000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40c000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40d000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40e000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab40f000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab410000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab411000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab412000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab413000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab414000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab415000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab416000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab417000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab418000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab419000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41a000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41b000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41c000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41d000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41e000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab41f000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab420000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab421000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab422000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab423000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab424000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab425000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab426000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab427000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab428000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab429000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42a000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42b000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42c000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42d000, 0xb1448000, 4096)
,V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42e000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab42f000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab430000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab431000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab432000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab433000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab434000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab435000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab436000, 0xb1448000, 4096)
V/AudioCache(  307): write(0xb1448000, 4096)
V/AudioCache(  307): memcpy(0xab437000, 0xb1448000, 4096)
V/OMXCodec(  307): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  307): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  307): postAudioEOS() 
V/AudioCache(  307): write(0xb1448000, 280)
V/AudioCache(  307): memcpy(0xab438000, 0xb1448000, 280)
V/AwesomePlayer(  307): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  307): onStreamDone
V/AwesomePlayer(  307): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  307): notify(0xb1163500, 2, 0, 0)
V/AudioCache(  307): playback complete
V/AwesomePlayer(  307): pause_l() 
V/AudioCache(  307): notify(0xb1163500, 7, 0, 0)
V/AudioCache(  307): ignored
V/AwesomePlayer(  307): cancelPlayerEvents
V/AudioCache(  307): wait - success
V/MediaPlayerService(  307): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  307): Pause Playback at 1068125
V/AwesomePlayer(  307): reset_l() 
V/AudioCache(  307): notify(0xb1163500, 8, 0, 0)
V/AudioCache(  307): ignored
V/AwesomePlayer(  307): cancelPlayerEvents
D/AudioPlayer(  307): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  307): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  307): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  307): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a600 on port 0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a470 on port 0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a380 on port 0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a290 on port 0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119ad80 on port 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a6a0 on port 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119a880 on port 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeing buffer 0xb119aa10 on port 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  307): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  307): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  307): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  307): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  307): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  307): AudioPlayer releasing audio source
D/AudioPlayer(  307): AudioPlayer done releasing audio source
V/AwesomePlayer(  307): reset_l() 
V/AwesomePlayer(  307): cancelPlayerEvents
V/AwesomePlayer(  307): ~AwesomePlayer call
V/AwesomePlayer(  307): reset_l() 
V/AwesomePlayer(  307): cancelPlayerEvents
V/SoundPool( 7277): close(30)
V/SoundPool( 7277): pointer = 0x9ffb7000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7277): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:506
,I/UEI.SmartControl( 6868): Supports setup maps: true
,D/UEI.SmartControl( 6868): QS start statue = true Error code = 0
I/UEI.SmartControl( 6868): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6868): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6868): ### init IR Blaster...
D/serial_port( 6868): Configuring serial port
E/UEI.SmartControl( 6868): UEIBLaster setting for 616
I/UEI.SmartControl( 6868): Setting serial record hearder size = 2
I/UEI.SmartControl( 6868): configuring settings for MAXQ616
I/UEI.SmartControl( 6868): Get version...
D/UEI.SmartControl( 6868): serial port data available: 21
,D/UEI.SmartControl( 6868): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6868): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6868): QS saving settings...
,D/UEI.SmartControl( 6868): IR Blaster version: 25672567
D/UEI.SmartControl( 6868): serial port data available: 4
,W/ContextImpl( 6868): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6868): Services init done
D/UEI.SmartControl( 6868): QS Service init finished
D/UEI.SmartControl( 6868): QS Service version name: 2.1.91
D/UEI.SmartControl( 6868): QS Service version code: 201091
D/UEI.SmartControl( 6868): Service requested: Control
I/QRemote ( 7277): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6868): ------ IControl API: 11
D/UEI.SmartControl( 6868): File observer start...
E/UEI.SmartControl( 6868): IR Port is disabled: false,
D/UEI.SmartControl( 6868): Starting file observer...
I/UEI.SmartControl( 6868): Registering callback...
I/UEI.SmartControl( 6868): ------ IControl API: 19
,I/UEI.SmartControl( 6868): Registering Services Ready callback...
D/UEI.SmartControl( 6868): Internal service binding...
I/UEI.SmartControl( 6868): Device manager: loading config....
D/UEI.SmartControl( 6868): ----------- loading internal config...
E/UEI.SmartControl( 6868): Loading SETTINGS...
,D/UEI.SmartControl( 6868): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6868): Notify AllClients services are ready: 0
,I/QRemote ( 7277): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6868): -----service ready thread exits
D/QRemote ( 7277): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7277): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7277): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7277): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6868): ------ IControl API: 8
D/QRemote ( 7277): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7277): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7277): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7277): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7277): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7277): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7277): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7277): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453885706095]
D/QRemote ( 7277): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6676:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7277): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6676/cgroup.procs: No such file or directory
,V/QRemote ( 7277): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7277): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7277): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2690): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS ,
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=268385  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=268391  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2690): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=268552  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=268553  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=268555
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=268556
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=268557
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=268558
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=268558
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2690): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=268561  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=268572  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=268575  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=268576  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=268576
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=268577
D/WifiNative-wlan0( 1037): doString: [STATUS]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7211): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7211): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7211): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7211): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  301): Setting iface cfg
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=268625  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=268625  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=268626  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=268632  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=268632  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=268633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11c7ad95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11c7ad95 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
,D/CommandListener(  301): Setting iface cfg
D/CommandListener(  301): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
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
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1954): handleWifiStateChangedEvent: 1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  301): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
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
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  301): res_queryN name = clients3.google.com, class = 1, type = 28
,D/TelephonyNetworkFactory-1( 1856): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1856):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
W/dsqn    ( 7359): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7359): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
,D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/DSQN    ( 7359): DSQN ssw
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/libc-netbsd(  301): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7277): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7277): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7277): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7277): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7247): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7247): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  301): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 7211): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7211): MCCMNC not supported: null
D/QRemote ( 7277): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7277): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7277): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7277): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7277): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  301): argv[0]=dsqncommand
D/LGDataListener(  301): argv[1]=wlan0
D/LGDataListener(  301): argv[2]=1
D/LGDataListener(  301): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 09:08:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453885707214], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453885707195]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
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
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
D/TelephonyNetworkFactory-1( 1856): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1856):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7365): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7365): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7365): version 5.5.6 starting
,E/dhcpcd  ( 7365): get_duid: m
D/dhcpcd  ( 7365): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7365): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7365): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7365): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7365): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7365): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7365): wlan0: sending REQUEST (xid 0xce314cd1), next in 3.26 seconds
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6618): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5475): type=WIFI subType= reason=null isConnected=true
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7389 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 392us total 9.410ms
I/art     (  329): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.573ms
,I/NetworkMonitor( 5475): type=WIFI subType= reason=null isConnected=true
I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 8.817ms
,I/AppUp4:AppBoxCP( 7389): onCreate
,W/AppUp4:DB( 7389):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7389):  setFingerPrint start
I/AppUp4:DB( 7389):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7389):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7389):  SDK version = 21
I/AppUp4:DB( 7389):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7389): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7389): onReceive
D/LgDataFeature( 7389): LgDataFeature() Constructor: none
D/LgDataFeature( 7389): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7389): Context : android.app.ReceiverRestrictedContext@d340bc1
D/AppUp4:CustFacade( 7389): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7389): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7389): begin check event
I/AppUp4:CustModeStarterReceiver( 7389): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7389): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7389): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7389): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7389): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6696:com.android.contacts/u0a19 (adj 15): empty #17
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6696/cgroup.procs: No such file or directory
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3414): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3414): DownloadService onCreate
I/LGDMClient( 4324): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3414): in removeSpuriousFiles
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@383ffd4c on behalf of 3414
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3414): in trimDatabase
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@27343195 on behalf of 3414
V/DownloadManager( 3414): DownloadService onStartCommand
,V/DownloadManager( 3414): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@2915a238 on behalf of 3414
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3414): processing inserted download 1
V/DownloadManager( 3414): processing inserted download 4
V/DownloadManager( 3414): processing inserted download 7
E/LGDMClient( 4324): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3414): processing inserted download 8
D/LGDMClient( 4324): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3414): processing inserted download 9
D/LGDMClient( 4324): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3414): processing inserted download 10
V/DownloadManager( 3414): processing inserted download 16
V/DownloadManager( 3414): processing inserted download 17
V/DownloadManager( 3414): processing inserted download 18
D/eas_req ( 6719): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3414): processing inserted download 21
V/DownloadManager( 3414): processing inserted download 22
V/DownloadManager( 3414): DownloadService onDestroy
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7418 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6719): JNI_OnLoad()
I/HubEmail( 6719): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6719): registerNatives()
I/HubEmail( 6719): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6719): registerNativeMethods()
I/HubEmail( 6719): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6719): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3354): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3354): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3354): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7441 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  301): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  301): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  301): res_queryN name = static-avc.lglime.com succeed
,I/dhcpcd  ( 7365): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,V/FormManager( 7418): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
I/dhcpcd  ( 7365): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7365): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7365): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7365): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7365): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7365): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7365): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7365): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7467 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6743:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6743/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6764:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7499 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6818:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6764/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6818/cgroup.procs: No such file or directory
I/art     ( 7499): Almond Protected OAT
,D/WeatherApplication( 7499): removeAccount
,D/WeatherApplication( 7499): Account.length = 0
E/WeatherApplication( 7499): OPERATOR:OPEN
D/WeatherAncestor( 7499): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:28
D/Weather.Utils( 7499): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7499): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7499): 2 : This is isUpdating : false
,D/WeatherAncestor( 7499): connectivity changed - connection : true
D/WeatherService( 7499): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7499): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7499): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7499): 2 : Cache is not up-to-date, count: 0
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
,D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524295
D/Weather_cast( 7499): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7499): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:28
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7517 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6898:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6898/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7517): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7517): Loading: webviewchromium
I/LibraryLoader( 7517): Time to load native libraries: 4 ms (timestamps 1134-1138)
,I/LibraryLoader( 7517): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7517): Binding Chromium to main looper Looper (main, tid 1) {8d749f0}
,I/LibraryLoader( 7517): Expected native library version number "",actual native library version number ""
I/chromium( 7517): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7517): Initializing chromium process, renderers=0
W/art     ( 7517): Attempt to remove local handle scope entry from IRT, ignoring
I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7127): 
W/chromium( 7517): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7517): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7517): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  307): registerClient() client 0xb1184ca0, uid 10093
W/AudioManagerAndroid( 7517): Requires BLUETOOTH permission
I/Adreno-EGL( 7517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7517): Build Date: 12/12/14 금
I/Adreno-EGL( 7517): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7517): Remote Branch: 
I/Adreno-EGL( 7517): Local Patches: 
I/Adreno-EGL( 7517): Reconstruct Branch: 
I/NSApplication( 7517): Starting up...
,I/ActivityManager( 1037): Killing 6072:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6072/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7389): onReceive
W/ContextImpl( 6618): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/AppUp4:CustFacade( 7389): Context : android.app.ReceiverRestrictedContext@d340bc1
D/AppUp4:CustFacade( 7389): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7389): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7389): begin check event
I/AppUp4:CustModeStarterReceiver( 7389): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3414): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3414): DownloadService onCreate
D/LGDMClient( 4324): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4324): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/LgeMiscReceiver( 3354): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3354): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3354): networkInfo.isConnected() = false
I/DownloadManager( 3414): in removeSpuriousFiles
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@8c14f76 on behalf of 3414
W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3414): in trimDatabase
E/LGDMClient( 4324): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3414): DownloadService onStartCommand
V/DownloadManager( 3414): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/art     ( 2116): Explicit concurrent mark sweep GC freed 44153(2MB) AllocSpace objects, 12(1623KB) LOS objects, 51% free, 30MB/62MB, paused 990us total 62.932ms
D/LGDMClient( 4324): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4324): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@1aa9fe4d on behalf of 3414
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=355636466, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@226aed02 on behalf of 3414
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1621c889 type 2 when 271557 com.google.android.gms} when 271557
V/DownloadManager( 3414): processing inserted download 1
V/DownloadManager( 3414): processing inserted download 4
V/DownloadManager( 3414): processing inserted download 7
V/DownloadManager( 3414): processing inserted download 8
,D/WeatherAncestor( 7499): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:29
V/DownloadManager( 3414): processing inserted download 9
V/DownloadManager( 3414): processing inserted download 10
V/DownloadManager( 3414): processing inserted download 16
V/DownloadManager( 3414): processing inserted download 17
V/DownloadManager( 3414): processing inserted download 18
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3414): processing inserted download 21
D/[Concierge]Service( 2595): onStartCommand(). Type : 9
,V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3414): processing inserted download 22
V/DownloadManager( 3414): DownloadService onDestroy
,D/Weather.Utils( 7499): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7499): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7499): 2 : This is isUpdating : false
D/WeatherAncestor( 7499): connectivity changed - connection : true
D/WeatherService( 7499): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3f6902a7
D/ForecastDataCache( 7499): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7499): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7499): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7499): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7499): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:29
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
V/FormManager( 7418): There are no updated forms. The schedule will be deleted.
V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{3ca53249 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=355636466 [*alarm*], flags=0x0
D/libc-netbsd(  301): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  301): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  301): res_queryN name = mtalk.google.com succeed
W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{3ca53249 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5475): type=WIFI subType= reason=null isConnected=true
D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 6618): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7389): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7389): onReceive
,D/AppUp4:CustFacade( 7389): Context : android.app.ReceiverRestrictedContext@d340bc1
D/AppUp4:CustFacade( 7389): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7389): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7389): begin check event
I/AppUp4:CustModeStarterReceiver( 7389): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4324): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3414): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4324): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4324): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3414): DownloadService onCreate
W/ContextImpl( 4324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4324): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4324): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4324): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3414): in removeSpuriousFiles
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@38e8050 on behalf of 3414
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3414): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3414): in trimDatabase
V/DownloadManager( 3414): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@151ed74e on behalf of 3414
,W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3414): DownloadService onStartCommand
V/DownloadManager( 3414): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3414): created cursor android.database.sqlite.SQLiteCursor@2663517c on behalf of 3414
I/LgeMiscReceiver( 3354): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3354): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3354): networkInfo.isConnected() = true
D/PhoneState( 3354): setPdpRejectCasuse : false
V/DownloadManager( 3414): processing inserted download 1
D/WeatherAncestor( 7499): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:30
,V/DownloadManager( 3414): processing inserted download 4
D/Weather.Utils( 7499): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7499): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7499): 2 : This is isUpdating : false
D/WeatherAncestor( 7499): connectivity changed - connection : true
D/WeatherService( 7499): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3f6902a7
D/ForecastDataCache( 7499): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7499): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7499): 2 : Cache is up-to-date, count: 0
V/DownloadManager( 3414): processing inserted download 7
D/Weather_cast( 7499): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7499): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:8:30
V/DownloadManager( 3414): processing inserted download 8
V/DownloadManager( 3414): processing inserted download 9
V/DownloadManager( 3414): processing inserted download 10
,V/DownloadManager( 3414): processing inserted download 16
V/DownloadManager( 3414): processing inserted download 17
V/DownloadManager( 3414): processing inserted download 18
I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7127): 
V/DownloadManager( 3414): processing inserted download 21
V/DownloadManager( 3414): processing inserted download 22
V/DownloadManager( 3414): DownloadService onDestroy
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7127): 
,I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7127): 
D/GCM     ( 2116): Connected
,I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7127): 
,I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7127): 
,I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7127): 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 94630(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.539ms total 126.862ms
,D/GCM     ( 2116): Message class com.google.f.a.a.p
I/GLSUser ( 2116): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2116): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2116): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2116): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2116): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 7127): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7127): 
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{3ca53249 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7418): There are no updated forms. The schedule will be deleted.,
,V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
D/UEI.SmartControl( 6868): Internal timer expired: 3
D/UEI.SmartControl( 6868): unbind internal service
,D/serial_port( 6868): close(fd = 24)
,I/UEI.SmartControl( 6868): Serial port is closed.
D/libc-netbsd(  301): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  301): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  301): res_queryN name = www.google.com succeed
,D/libc-netbsd(  301): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  301): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  301): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7517): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7127): Test app app.js loaded
I/jxcore-log( 7127): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7127): setDiscoveryMode: Mode set to BLE
,I/chromium( 7127): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 7127): BLE advertisement is supported
I/jxcore-log( 7127): 
,I/jxcore-log( 7127): --= Surplus to requirements =--
I/jxcore-log( 7127): 
I/jxcore-log( 7127): ****TEST TOOK:  ms ****
I/jxcore-log( 7127): 
I/jxcore-log( 7127): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7127): 
,D/AndroidRuntime( 7618): 
D/AndroidRuntime( 7618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7618): CheckJNI is OFF
,D/AndroidRuntime( 7618): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 7127:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1037): WIN DEATH: Window{2e3c0d7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{2e3c0d7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{266f689e com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2a61ff27 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  325): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{2c97428f 7127:com.test.thalitest/u0a311}, curProc for 7127: null
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2a61ff27 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{2a61ff27 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2073): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{d1f7d1 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2073): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1954): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1954): topRunningActivity=ActivityInfo{f8e6236 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2073): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1908): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3736): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2073): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
,E/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3818): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,D/LIA_MrGDBLogger_PackageInfoDetector( 3736): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/[LGHome]EVENT( 2073): [Launcher.java:1056:onResume()]onResume end
,D/PostponalbeReceiver( 6618): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4547): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4547): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4547): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4547): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4547): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4547): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4547): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4547): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4547): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4547): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7642 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2073): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1908): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3736): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2073): , create_time: 1430558575574
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2073): , create_time: 1430558575600
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2073): , create_time: 1453384801850
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
D/WallpaperManager( 2073): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_REMOVED
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27ef2af6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/art     ( 4601): Explicit concurrent mark sweep GC freed 16110(914KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 397us total 206.775ms
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1873): split_name #11 / not available #0
D/SplitUIService( 1873): removed split : 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 12368(1001KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.809ms total 225.918ms
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
I/art     ( 1037): WaitForGcToComplete blocked for 45.174ms for cause Explicit
D/AppUp4:PreloadHelper( 7389): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2073): [Launcher.java:5349:onStop()]onStop
,D/SplitUIManager( 1873): split_name #11 / not available #0
I/SplitUIService( 1873): split app #11
I/LockScreenSettings( 7642): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7664 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
,D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
D/administrator( 1037): Handling package changes for user 0
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
I/ActivityManager( 1037): Killing 6927:com.lge.bnr/1000 (adj 15): empty #17
,W/ResourcesManager( 7664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7664): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7664): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7664): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7664): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ThermalEngine(  319): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3133): Thermal-Lib-Client: Client request sent
,I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,D/KeyguardModel( 1445): handleShortcutListChanged...
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6927/cgroup.procs: No such file or directory
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{a80c0d1 u0 com.lge.launcher2/.Launcher t3} time:277941
D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
,D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1445): createShortcutInfo...
I/[Concierge]WidgetView( 2073): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/[Concierge]Service( 2595): onStartCommand(). Type : 8
D/[Concierge]Service( 2595): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
D/[Concierge]Service( 2595): Update widget ID : 11
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
D/[Concierge]WidgetView( 2073): change position of spinner
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1445): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
I/[Concierge]WidgetView( 2073): initWebView(). Time : 1453885716293
D/[Concierge]Service( 2595): onStartCommand(). Type : 0
,D/KeyguardModel( 1445): handleShortcutListChanged...
I/[Concierge]WebView( 2073): Return exist ConciergeWebView. Reuse : 933399142
I/SystemConfig( 7664): BUILD Country: EU
I/SystemConfig( 7664): BUILD Operator: OPEN
D/[Concierge]WidgetView( 2073): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2073): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@36dc6e57
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2073): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2073): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2073): Widget kill message received. Destory myself. My : 1453885466304, New one : 1453885716293
D/[Concierge]WidgetView( 2073): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2073): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277998358230; DSPS: 9250308; Offset : -4314690713
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1037): Killing 6991:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1037): Explicit concurrent mark sweep GC freed 9344(511KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.330ms total 251.263ms
,I/Timeline( 2073): Timeline: Activity_idle id: android.os.BinderProxy@1298ce0a time:278065
,W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6991/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 2186): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7664): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7664): existFile = false
I/SystemConfig( 7664): canReadFile = false
I/SystemConfig( 7664): systemFeature RCS result false
D/SystemConfig( 7664): refreshRcsSupport() :false
I/PackageChangeReceiver( 6719): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7688 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7688): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7688): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/AndroidRuntime( 7618): Shutting down VM
I/chromium( 2073): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/AppConfig( 7688): Total System Memory = 2995761152
,D/SystemHelper( 7688): region [EU], country [EU], operator [OPEN], sub-operator []
I/GBoardtInterface( 2073): onReloaded()
,I/GBoardWebViewClient( 2073): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 3736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1908): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3736): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3736): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1908): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3736): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3736): onEvent() : ACTION_BOARD_ENABLED
,D/LIA_Informant_Tips_FormEventRepository( 3736): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3736): onSettingEvent() : GBoard On - add scheduler - 0
I/ActivityManager( 1037): Killing 6250:com.android.vending/u0a44 (adj 15): empty #17
V/BoardContentProvider( 3736): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Service_NativeEventReceiver( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2030): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6250/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2030): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/GBoardUriUtils( 2073): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,D/GBoardWebViewUtils( 2073): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/PostponalbeReceiver( 6618): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/GBoardUriUtils( 2073): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2073): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2073): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2073): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7708 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 7708): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 7708): No ProfileInfo entries
I/LG Account v2.2( 7708): isEnabled: false
I/Feature ( 7708): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7708): [Lifetracker]Country: EU
I/Feature ( 7708): [Lifetracker]Operator: OPEN
I/Feature ( 7708): [Lifetracker]Ranking support: false
I/Feature ( 7708): [Lifetracker]Comfort support: false
I/Feature ( 7708): [Lifetracker]Accessory: true
I/Feature ( 7708): [Lifetracker]Health device: true
I/Feature ( 7708): [Lifetracker]Extra Pedometer: false
I/Feature ( 7708): [Lifetracker]Blood glucose device: false
I/Feature ( 7708): [Lifetracker]Device Number: 3
,D/CoreEventReceiver( 7708): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7211): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7211): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,D/HideNavigationAppsReceiver( 7211): replacing : false
D/HideNavigationAppsReceiver( 7211): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7211): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7211): replacing : false
I/ActivityManager( 1037): Killing 7247:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7247/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4601): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/ActivityManager( 1037): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7732 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 4601): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/IcingCorporaProvider( 4601): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 4601): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 4601): 	at beg.a(PG:301)
E/IcingCorporaProvider( 4601): 	at beg.c(PG:222)
E/IcingCorporaProvider( 4601): 	at cun.b(PG:660)
E/IcingCorporaProvider( 4601): 	at cun.a(PG:651)
E/IcingCorporaProvider( 4601): 	at cun.g(PG:597)
E/IcingCorporaProvider( 4601): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 4601): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/IcingCorporaProvider( 4601): 	at android.content.ContentResolver.update(ContentResolver.java:1349)
E/IcingCorporaProvider( 4601): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 4601): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 4601): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 4601): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 4601): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 4601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 4601): 	at android.os.Looper.loop(Looper.java:135)
E/IcingCorporaProvider( 4601): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 4601): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/IcingCorporaProvider( 4601): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/IcingCorporaProvider( 4601): 	at bea.a(PG:382)
E/IcingCorporaProvider( 4601): 	at beg.i(PG:325)
E/IcingCorporaProvider( 4601): 	at beh.call(PG:215)
E/IcingCorporaProvider( 4601): 	at beg.a(PG:299)
E/IcingCorporaProvider( 4601): 	... 15 more
W/IcingCorporaProvider( 4601): notifyTableChanged failed.
W/IcingCorporaProvider( 4601): Table change notification failed for TableStorageSpec[applications]
,I/UpdateIcingCorporaServi( 4601): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
D/DocsApplication( 7732): Installing DEX configuration.
,I/GBoardtInterface( 2073): exportHTML()
,D/DexInstaller( 7732): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7732): Provided clientMode=RELEASE, packageInfo=PackageInfo{2c862caf com.google.android.apps.docs}
D/TAG     ( 7732): onCreate()
D/CrossAppStateProvider( 7732): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/GBoardtInterface( 2073): exportHTML()
,I/GBoardtInterface( 2073): exportHTML()

```
