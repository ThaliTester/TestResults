#### Test 558973767bac5c9_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 258034921094; DSPS: 8596067; Offset : -4308471602
,D/AndroidRuntime( 7091): 
D/AndroidRuntime( 7091): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7091): CheckJNI is OFF
D/AndroidRuntime( 7091): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1980): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{1ff73b90 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{1ff73b90 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7110 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7091): Shutting down VM
I/art     ( 1038): Explicit concurrent mark sweep GC freed 27011(1180KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.662ms total 72.957ms
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1879): Display #0 changed.
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{deaa6e8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{2b33f101 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7110): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7110): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7110): Loading: webviewchromium
,I/LibraryLoader( 7110): Time to load native libraries: 9 ms (timestamps 6012-6021)
I/LibraryLoader( 7110): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7110): Binding Chromium to main looper Looper (main, tid 1) {300ed098}
I/LibraryLoader( 7110): Expected native library version number "",actual native library version number ""
I/chromium( 7110): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7110): Initializing chromium process, renderers=0
W/art     ( 7110): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  324): registerClient() client 0xb165cd60, uid 10311
,W/chromium( 7110): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7110): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7110): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e95fb9a:true
I/Adreno-EGL( 7110): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7110): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7110): Build Date: 12/12/14 금
I/Adreno-EGL( 7110): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7110): Remote Branch: 
I/Adreno-EGL( 7110): Local Patches: 
I/Adreno-EGL( 7110): Reconstruct Branch: 
,W/chromium( 7110): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7110): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7110): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7110): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7110): CordovaWebView is running on device made by: LGE
,W/art     ( 7110): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7110): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7110): Render dirty regions requested: true
I/OpenGLRenderer( 7110): Initialized EGL, version 1.4
D/OpenGLRenderer( 7110): Enabling debug mode 0
D/Atlas   ( 7110): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{34891184 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c7b0041,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 7110): LgDataFeature() Constructor: none
D/LgDataFeature( 7110): LgDataFeature() Constructor Done, null
,I/Timeline( 7110): Timeline: Activity_idle id: android.os.BinderProxy@ba38fc8 time:266398
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +542ms (total +709ms)
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{11ca6c89 u0 com.test.thalitest/.MainActivity t4} time:266416
D/JsMessageQueue( 7110): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7110): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7110): 
,D/jxcore_app_log( 7110): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435069184
,I/chromium( 7110): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7110): 
I/chromium( 7110): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7110): Initializing JXcore engine
W/jxcore-log( 7110): JXcore engine is ready
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3447c1f0 type 2 when 238370 android} when 238370
W/Thread-829( 7180): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10284]" dev="sockfs" ino=10284 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-829( 7180): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-829( 7180): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7732]" dev="sockfs" ino=7732 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-829( 7180): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-829( 7180): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34947]" dev="sockfs" ino=34947 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7110): Starting JXcore engine
,W/jxcore-log( 7110): Platform android
W/jxcore-log( 7110): 
W/jxcore-log( 7110): Process ARCH arm
W/jxcore-log( 7110): 
I/jxcore-log( 7110): JXcore Cordova bridge is ready!
I/jxcore-log( 7110): 
W/jxcore-log( 7110): JXcore engine is started
I/jxcore-log( 7110): Toggling radios to true
I/jxcore-log( 7110): 
D/BluetoothAdapter( 7110): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7110, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7110, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7110, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [268,760,362 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7110, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7110): Radios toggled
I/jxcore-log( 7110): 
I/jxcore-log( 7110): My device name is: LGE-LG-D855
I/jxcore-log( 7110): 
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  320): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2145): Read error: ssl=0xaf499600: I/O error during system call, Connection timed out
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaf499600: I/O error during system call, Broken pipe
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiNative: ( 1038): [268,855,916 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268891
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268892
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  320): Clearing all IP addresses on wlan0
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268932  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268933  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
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
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
W/ResourcesManager( 7200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7200): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/ResourcesManager( 7200): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 7200): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7200): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7200): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1879): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1879):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7200): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7200): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7200): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7200): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-201ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6679:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6679/cgroup.procs: No such file or directory
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7200): LgDataFeature() Constructor: none
D/LgDataFeature( 7200): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7261 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6183:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/art     (  347): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 22.861ms
I/art     (  347): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 19.835ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 18.428ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6183/cgroup.procs: No such file or directory
,W/ResourcesManager( 7261): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7261): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7261): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7261): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7261): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7261): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7261): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7261): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7261): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7261): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7261): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7237): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7261): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7261): LgDataFeature() Constructor: none
D/LgDataFeature( 7261): LgDataFeature() Constructor Done, null
,V/SoundPool( 7261): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7261): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7261): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7261): doLoad: loading sample sampleID=1
I/QRemote ( 7261): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7261): Start decode
V/MediaPlayer[Native]( 7261): decode(31, 10857164, 17813)
D/UEI.SmartControl( 6827): QS Service created
,V/MediaPlayerService(  324): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  324): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  324): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  324): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  324): player type = 3
V/AwesomePlayer(  324): AwesomePlayer create()
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): setAudioSink() 
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb1432c00, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/Utils   (  324): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  324): setDataSource_l dataSource
V/LGParserOSAL(  324): SniffLGParser start
V/LGParserOSAL(  324): MainType:5, SubType=0
V/LGParserOSAL(  324): #### check Mime : application/ogg
V/LGParserOSAL(  324): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  324): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6827): Service initServices...
D/UEI.SmartControl( 6827): QS start get config
,V/LGParserOSAL(  324): supported mime: application/ogg
V/AwesomePlayer(  324): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  324): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  324): mBitrate = -1 bits/sec
V/AwesomePlayer(  324): AudioTrack Setting
V/AwesomePlayer(  324): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  324): setAudioSource() 
V/MediaPlayerService(  324): prepare
V/AwesomePlayer(  324): prepareAsync_l() 
V/MediaPlayerService(  324): wait for prepare
V/AwesomePlayer(  324): onPrepareAsyncEvent() 
V/AwesomePlayer(  324): initAudioDecoder() 
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
,I/AudioFlinger(  324): isAudioPlaybackHookOn() false
V/AwesomePlayer(  324): getUseOffload() = 0 
V/OMXCodec(  324): OMXCodec::Create
V/OMXCodec(  324): findMatchingCodecs()
V/OMXCodec(  324): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  324): matchingCodecs.size()=1
V/OMXCodec(  324): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  324): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  324): LG Codec Adapter start
V/OMXCodec(  324): OMXCodec Createtor
D/QRemote ( 7261): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/OMXCodec(  324): setComponentRole
V/OMXCodec(  324): configureCodec protected=0
V/LGCodecAdapter(  324): called getLGCodecSpecificData
V/LGCodecOSAL(  324): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMSG
V/LGCodecOSAL(  324): Not support LGCodec
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  324): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  324): Could not offload audio decode, try pcm offload
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  324): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  324): init()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,V/OMXCodec(  324): allocateBuffers
V/OMXCodec(  324): allocateBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  324): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  324): finishAsyncPrepare_l() 
V/AudioCache(  324): notify(0xb1432c00, 5, 0, 0)
V/AudioCache(  324): ignored
V/AudioCache(  324): notify(0xb1432c00, 1, 0, 0)
V/AudioCache(  324): prepared
V/AudioCache(  324): wait - success
V/MediaPlayerService(  324): start
V/AwesomePlayer(  324): play_l() 
V/AwesomePlayer(  324): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  324): createAudioPlayer_l
V/AwesomePlayer(  324): seekAudioIfNecessary_l() 
V/AwesomePlayer(  324): startAudioPlayer_l() 
D/AudioPlayer(  324): start of Playback, useOffload 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  324): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795744
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  324): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb17503d0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  324): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  324): notify(0xb1432c00, 6, 0, 0)
,V/AudioCache(  324): ignored
V/MediaPlayerService(  324): wait for playback complete
V/LGMDMManager( 7261): Create singleton instance
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab504000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab505000, 0xb57c8000, 4096)
,V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab506000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab507000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab508000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab509000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50a000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50b000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50c000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50d000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50e000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab50f000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab510000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab511000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab512000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab513000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab514000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab515000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab516000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab517000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab518000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab519000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51a000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51b000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51c000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51d000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51e000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab51f000, 0xb57c8000, 4096)
,V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab520000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab521000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab522000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab523000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab524000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab525000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab526000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab527000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab528000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab529000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52a000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52b000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52c000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52d000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52e000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab52f000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab530000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab531000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab532000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab533000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab534000, 0xb57c8000, 4096)
V/AudioCache(  324): write(0xb57c8000, 4096)
V/AudioCache(  324): memcpy(0xab535000, 0xb57c8000, 4096)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  324): postAudioEOS() 
V/AudioCache(  324): write(0xb57c8000, 280)
V/AudioCache(  324): memcpy(0xab536000, 0xb57c8000, 280)
V/AwesomePlayer(  324): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  324): onStreamDone
V/AwesomePlayer(  324): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  324): notify(0xb1432c00, 2, 0, 0)
V/AudioCache(  324): playback complete
V/AwesomePlayer(  324): pause_l() 
V/AudioCache(  324): notify(0xb1432c00, 7, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
V/AudioCache(  324): wait - success
V/MediaPlayerService(  324): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  324): Pause Playback at 1068125
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb1432c00, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIn,dex=0,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb17503d0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  324): AudioPlayer releasing audio source
D/AudioPlayer(  324): AudioPlayer done releasing audio source
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): ~AwesomePlayer call
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/SoundPool( 7261): close(31)
V/SoundPool( 7261): pointer = 0x9fe75000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7261): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7261): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7958
I/UEI.SmartControl( 6827): Supports setup maps: true
D/UEI.SmartControl( 6827): QS start statue = true Error code = 0,
I/UEI.SmartControl( 6827): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6827): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6827): ### init IR Blaster...
,D/serial_port( 6827): Configuring serial port,
E/UEI.SmartControl( 6827): UEIBLaster setting for 616
I/UEI.SmartControl( 6827): Setting serial record hearder size = 2
I/UEI.SmartControl( 6827): configuring settings for MAXQ616
I/UEI.SmartControl( 6827): Get version...
D/UEI.SmartControl( 6827): serial port data available: 21
,D/UEI.SmartControl( 6827): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6827): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6827): QS saving settings...
D/UEI.SmartControl( 6827): IR Blaster version: 25672567
,D/UEI.SmartControl( 6827): serial port data available: 4
,W/ContextImpl( 6827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6827): Device manager: loading config....
E/UEI.SmartControl( 6827): Services init done
,D/UEI.SmartControl( 6827): QS Service init finished
D/UEI.SmartControl( 6827): QS Service version name: 2.1.91
D/UEI.SmartControl( 6827): QS Service version code: 201091
D/UEI.SmartControl( 6827): Service requested: Control
D/UEI.SmartControl( 6827): ----------- loading internal config...
E/UEI.SmartControl( 6827): Loading SETTINGS...
D/UEI.SmartControl( 6827): Request IControl service: devices are loaded...
I/QRemote ( 7261): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6827): Internal service binding...
I/UEI.SmartControl( 6827): ------ IControl API: 11
D/UEI.SmartControl( 6827): File observer start...
E/UEI.SmartControl( 6827): IR Port is disabled: false
D/UEI.SmartControl( 6827): Starting file observer...
I/UEI.SmartControl( 6827): Registering callback...
,I/UEI.SmartControl( 6827): ------ IControl API: 19
I/UEI.SmartControl( 6827): Registering Services Ready callback...
D/UEI.SmartControl( 6827): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6827): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6827): -----service ready thread exits
I/QRemote ( 7261): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7261): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7261): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7261): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7261): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6827): ------ IControl API: 8
D/QRemote ( 7261): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7261): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7261): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7261): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7261): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7261): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7261): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7261): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452693353557]
D/QRemote ( 7261): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1038): Killing 6203:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7261): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6203/cgroup.procs: No such file or directory
,V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7261): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2698): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=271120  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=271137  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
,D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
,D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2698): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=271218  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=271219  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=271219
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=271220
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=271220
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=271220
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=271221
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=271221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2698): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
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
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=271226  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=271235  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=271235  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=271236
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=271236
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7200): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7200): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7200): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7200): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7200): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  320): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=271302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=271302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=271303  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=271309  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=271310  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=271310  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2eaddd10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2eaddd10 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  320): Setting iface cfg
D/CommandListener(  320): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
,D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2698): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService( 1038): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1038): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 1
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/Netd    (  320): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1879): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1879):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network t,ype 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
W/dsqn    ( 7331): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7331): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7331): DSQN ssw
D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7261): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7261): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7261): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7261): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7237): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7237): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7200): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7200): MCCMNC not supported: null
D/QRemote ( 7261): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7261): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
D/QRemote ( 7261): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/QRemote ( 7261): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7261): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
W/dhcpcd  ( 7335): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7335): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7335): version 5.5.6 starting
E/dhcpcd  ( 7335): get_duid: m
D/dhcpcd  ( 7335): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/LGDataListener(  320): argv[0]=dsqncommand
D/LGDataListener(  320): argv[1]=wlan0
D/LGDataListener(  320): argv[2]=1
D/LGDataListener(  320): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 13:55:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452693354791], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452693354772]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
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
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1879): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1879):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7335): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7335): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7335): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7335): wlan0: sending REQUEST (xid 0x193be2ea), next in 3.79 seconds
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5936): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5936): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7365 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7365): onCreate
,W/AppUp4:DB( 7365):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7365):  setFingerPrint start
I/AppUp4:DB( 7365):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7365):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7365):  SDK version = 21
I/AppUp4:DB( 7365):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7365): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7365): onReceive
,D/LgDataFeature( 7365): LgDataFeature() Constructor: none
D/LgDataFeature( 7365): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7365): Context : android.app.ReceiverRestrictedContext@239b14d6
D/AppUp4:CustFacade( 7365): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7365): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7365): begin check event
I/AppUp4:CustModeStarterReceiver( 7365): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7365): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7365): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7365): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7365): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6707:com.lge.email/u0a23 (adj 15): empty #17
,D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6707/cgroup.procs: No such file or directory
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{d5d0e13 type 2 when 272225 com.google.android.gms} when 272225
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3421): DownloadService onCreate
I/LGDMClient( 4362): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@24e084b on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@c509b41 on behalf of 3421
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7393 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3421): DownloadService onStartCommand
,V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1f72de27 on behalf of 3421
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
E/LGDMClient( 4362): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,V/DownloadManager( 3421): processing inserted download 7
D/LGDMClient( 4362): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4362): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
,V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
V/DownloadManager( 3421): processing inserted download 21
V/DownloadManager( 3421): DownloadService onDestroy
,W/ResourcesManager( 7393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7393): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7393): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7393): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7393): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7393): LgDataFeature() Constructor: none
D/LgDataFeature( 7393): LgDataFeature() Constructor Done, null
,D/eas_req ( 7393): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7421 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7393): JNI_OnLoad()
I/HubEmail( 7393): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7393): registerNatives()
I/HubEmail( 7393): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7393): registerNativeMethods()
I/HubEmail( 7393): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7393): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Killing 6231:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6231/cgroup.procs: No such file or directory
W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7444 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7467 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6592:com.android.defcontainer/u0a4 (adj 15): empty #17
I/dhcpcd  ( 7335): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7335): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 7335): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7335): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7335): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7335): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7335): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524295
W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6592/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7503 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6741:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6741/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com succeed
,I/art     ( 7503): Almond Protected OAT
,V/FormManager( 7421): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7421): Alarm would be updated, because LastCheckTime has been updated.
,D/WeatherApplication( 7503): removeAccount
,D/WeatherApplication( 7503): Account.length = 0
E/WeatherApplication( 7503): OPERATOR:OPEN
D/WeatherAncestor( 7503): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:56
D/Weather.Utils( 7503): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7503): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7503): 2 : This is isUpdating : false
D/WeatherAncestor( 7503): connectivity changed - connection : true
D/WeatherService( 7503): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7503): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7503): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7503): 2 : Cache is not up-to-date, count: 0
I/ActivityManager( 1038): Killing 6791:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/Weather_cast( 7503): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7503): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:56
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6791/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7526 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6858:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7526): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7526): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7526): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7526): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,I/WebViewFactory( 7526): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7526): Loading: webviewchromium
,I/LibraryLoader( 7526): Time to load native libraries: 5 ms (timestamps 4468-4473)
I/LibraryLoader( 7526): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7526): Binding Chromium to main looper Looper (main, tid 1) {3d65b299}
,I/LibraryLoader( 7526): Expected native library version number "",actual native library version number ""
I/chromium( 7526): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/BrowserStartupController( 7526): Initializing chromium process, renderers=0
W/art     ( 7526): Attempt to remove local handle scope entry from IRT, ignoring
I/NetworkMonitor( 5936): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/chromium( 7526): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7526): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7526): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  324): registerClient() client 0xb165cda0, uid 10093
,W/AudioManagerAndroid( 7526): Requires BLUETOOTH permission
I/Adreno-EGL( 7526): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7526): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7526): Build Date: 12/12/14 금
I/Adreno-EGL( 7526): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7526): Remote Branch: 
I/Adreno-EGL( 7526): Local Patches: 
I/Adreno-EGL( 7526): Reconstruct Branch: 
,I/NSApplication( 7526): Starting up...
,I/ActivityManager( 1038): Killing 6881:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6881/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7365): onReceive
,D/AppUp4:CustFacade( 7365): Context : android.app.ReceiverRestrictedContext@239b14d6
D/AppUp4:CustFacade( 7365): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7365): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7365): begin check event
I/AppUp4:CustModeStarterReceiver( 7365): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4362): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4362): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LGDMClient( 4362): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4362): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3421): DownloadService onCreate
D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@364aaa7d on behalf of 3421
,I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@202535c3 on behalf of 3421
V/DownloadManager( 3421): DownloadService onStartCommand
,V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@30dc7179 on behalf of 3421
I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = false
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
,V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
D/WeatherAncestor( 7503): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:58
D/Weather.Utils( 7503): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7503): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7503): 2 : This is isUpdating : false
D/WeatherAncestor( 7503): connectivity changed - connection : true
D/WeatherService( 7503): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@146c5e44
D/ForecastDataCache( 7503): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7503): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7503): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7503): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7503): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:58
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3421): processing inserted download 16
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3421): processing inserted download 17
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
V/DownloadManager( 3421): processing inserted download 18
,V/DownloadManager( 3421): processing inserted download 21
V/DownloadManager( 3421): DownloadService onDestroy
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35055ebe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = mtalk.google.com, class = 1, type = 1
V/FormManager( 7421): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7421): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  320): res_queryN name = mtalk.google.com succeed
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 88192(4MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.703ms total 100.382ms
,D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7365): onReceive
D/AppUp4:CustFacade( 7365): Context : android.app.ReceiverRestrictedContext@239b14d6
D/AppUp4:CustFacade( 7365): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7365): isPhone : true
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/AppUp4:CustModeStarterReceiver( 7365): begin check event
I/AppUp4:CustModeStarterReceiver( 7365): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LGDMClient( 4362): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
I/LGDMClient( 4362): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4362): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3421): DownloadService onCreate
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
W/ContextImpl( 4362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,I/DownloadManager( 3421): in removeSpuriousFiles
E/LGDMClient( 4362): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4362): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4362): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@3b1b6b1f on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35055ebe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/DownloadManager( 3421): DownloadService onStartCommand
W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3371): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3371): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3371): networkInfo.isConnected() = true
D/PhoneState( 3371): setPdpRejectCasuse : false
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 7393): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@2234a8ca on behalf of 3421
,V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@32159a3b on behalf of 3421
D/WeatherAncestor( 7503): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:58
D/Weather.Utils( 7503): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7503): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7503): 2 : This is isUpdating : false
D/WeatherAncestor( 7503): connectivity changed - connection : true
D/WeatherService( 7503): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@146c5e44
D/ForecastDataCache( 7503): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7503): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7503): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7503): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7503): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:55:58
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
,V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
V/DownloadManager( 3421): processing inserted download 21
V/DownloadManager( 3421): DownloadService onDestroy
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7421): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7421): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{35055ebe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6827): Internal timer expired: 2
D/UEI.SmartControl( 6827): unbind internal service
,D/serial_port( 6827): close(fd = 24)
,I/UEI.SmartControl( 6827): Serial port is closed.
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  320): res_queryN name = www.google.com succeed
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=297071448, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/QRemote ( 7261): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7261): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7958
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=297071448 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 278036169897; DSPS: 9251468; Offset : -4308474175
,I/GAV4    ( 7526): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7110): Test app app.js loaded
I/jxcore-log( 7110): 
,I/chromium( 7110): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7110): --= Surplus to requirements =--
I/jxcore-log( 7110): 
I/jxcore-log( 7110): ****TEST TOOK:  ms ****
I/jxcore-log( 7110): 
I/jxcore-log( 7110): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7110): 
,D/AndroidRuntime( 7652): 
D/AndroidRuntime( 7652): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7652): CheckJNI is OFF
D/AndroidRuntime( 7652): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7110:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1038): Skipping PackageSetting{3435b40e com.example.hello/10319} due to missing metadata
,I/WindowState( 1038): WIN DEATH: Window{34891184 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{34891184 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{11ca6c89 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{11ca6c89 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{11ca6c89 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1038): Spurious death for ProcessRecord{3abc7c7a 7110:com.test.thalitest/u0a311}, curProc for 7110: null
,D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{20521ba6 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{fc689e7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2089): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2089): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2089): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     ( 4628): Explicit concurrent mark sweep GC freed 16103(914KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 590us total 62.651ms
D/ActionManagerService( 1933): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3753): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [+] updateMediaPlayerInfo
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2052): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3753): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 16558(1123KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 2.051ms total 128.764ms
,I/art     ( 1038): WaitForGcToComplete blocked for 51.763ms for cause Explicit
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
,D/PostponalbeReceiver( 6649): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]LGActivityUtil( 2089): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2089): [Launcher.java:1056:onResume()]onResume end
D/administrator( 1038): Handling package changes for user 0
,I/[LGHome]EVENT( 2089): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1933): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
W/System.err( 4583): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4583): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4583): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4583): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4583): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4583): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4583): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4583): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4583): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4583): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/LIA_Informant_ActionManagerMessageHandler( 3753): handleMessage: what(1000) actionID(0x1000004)
D/AppUp4:PreloadHelper( 7365): added Exclude : com.test.thalitest
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7686 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/SplitUIManager( 1899): split_name #11 / not available #0
D/SplitUIService( 1899): removed split : 
,V/BoardContentProvider( 3753): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/SplitUIManager( 1899): split_name #11 / not available #0
I/SplitUIService( 1899): split app #11
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7703 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3835): [BTUI] [-] updateMediaPlayerInfo
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2089): , create_time: 1430558575574
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2089): , create_time: 1430558575600
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2089): , create_time: 1452175675684
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
,D/WallpaperManager( 2089): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c7b0041,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
I/LockScreenSettings( 7686): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 7703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     ( 1038): Explicit concurrent mark sweep GC freed 5594(302KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.065ms total 233.011ms
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
,D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/art     ( 2089): Background sticky concurrent mark sweep GC freed 1942(110KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 5.075ms total 12.520ms
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2089): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/ActivityManager( 1038): Killing 6911:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/ThermalEngine(  336): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3187): Thermal-Lib-Client: Client request sent
,I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 7652): Shutting down VM
,I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1466): handleShortcutListChanged...
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6911/cgroup.procs: No such file or directory
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{47fa01 u0 com.lge.launcher2/.Launcher t3} time:282374
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/KeyguardModel( 1466): handleShortcutListChanged...
I/[Concierge]WidgetView( 2089): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2631): onStartCommand(). Type : 8
D/[Concierge]Service( 2631): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2631): Update widget ID : 11
I/SystemConfig( 7703): BUILD Country: EU
I/SystemConfig( 7703): BUILD Operator: OPEN
D/[Concierge]WidgetView( 2089): change position of spinner
D/[Concierge]Service( 2631): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2089): initWebView(). Time : 1452693365589
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WebView( 2089): Return exist ConciergeWebView. Reuse : 164586392
D/[Concierge]WidgetView( 2089): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2089): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3f00cfa0
,I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1038): Killing 6997:com.google.android.apps.books/u0a54 (adj 15): empty #17
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2089): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2089): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6997/cgroup.procs: No such file or directory
,W/[Concierge]WidgetView( 2089): Widget kill message received. Destory myself. My : 1452693111625, New one : 1452693365589
D/[Concierge]WidgetView( 2089): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2089): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/SystemConfig( 7703): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7703): existFile = false
I/SystemConfig( 7703): canReadFile = false
I/SystemConfig( 7703): systemFeature RCS result false
D/SystemConfig( 7703): refreshRcsSupport() :false
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 7393): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2163): Cleaning up data for package: com.test.thalitest
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7731 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7731): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/Timeline( 2089): Timeline: Activity_idle id: android.os.BinderProxy@1c9d882b time:282528
I/AppConfig( 7731): Total System Memory = 2995761152
,D/SystemHelper( 7731): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1038): Killing 6299:com.android.vending/u0a44 (adj 15): empty #17
,I/chromium( 2089): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LIA_Service_NativeEventReceiver( 2052): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2052): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6299/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2052): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6649): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/GBoardtInterface( 2089): onReloaded()
I/GBoardWebViewClient( 2089): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7754 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BoardContentProvider( 3753): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3753): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1933): notifyUserLog: 1000001
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 9.409ms
D/LIA_Informant_ActionManagerMessageHandler( 3753): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 3753): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1933): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3753): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3753): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3753): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3753): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3753): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 9.200ms
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
