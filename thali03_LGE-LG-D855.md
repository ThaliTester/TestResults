#### Test 56151093f3290d6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1469): called onTimeUpdated()
I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/AndroidRuntime( 7084): 
D/AndroidRuntime( 7084): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7084): CheckJNI is OFF
D/AndroidRuntime( 7084): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1033): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1970): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1033): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{3425c7c0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{3425c7c0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1033): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1033): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7105 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7084): Shutting down VM
V/ActivityManager( 1033): Display changed displayId=0
D/DSDPConnection( 1875): Display #0 changed.
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{248ddc53 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{4ba4990 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7105): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7105): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7105): Loading: webviewchromium
I/LibraryLoader( 7105): Time to load native libraries: 4 ms (timestamps 6491-6495)
,I/LibraryLoader( 7105): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7105): Binding Chromium to main looper Looper (main, tid 1) {3add70c3}
I/LibraryLoader( 7105): Expected native library version number "",actual native library version number ""
I/chromium( 7105): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7105): Initializing chromium process, renderers=0
W/art     ( 7105): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  321): registerClient() client 0xb54f4c80, uid 10311
,D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ac0a64a:true
W/chromium( 7105): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7105): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7105): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7105): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7105): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7105): Build Date: 12/12/14 금
I/Adreno-EGL( 7105): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7105): Remote Branch: 
I/Adreno-EGL( 7105): Local Patches: 
I/Adreno-EGL( 7105): Reconstruct Branch: 
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 26672(1171KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.727ms total 102.466ms
,W/chromium( 7105): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7105): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7105): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7105): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager( 1033): Activity pause timeout for ActivityRecord{3572bcf9 u0 com.test.thalitest/.MainActivity t4}
,D/SystemWebViewEngine( 7105): CordovaWebView is running on device made by: LGE
W/art     ( 7105): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7105): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7105): Render dirty regions requested: true
I/OpenGLRenderer( 7105): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7105): Enabling debug mode 0
D/Atlas   ( 7105): Validating map...
,D/SplitWindow( 1033): check instance of lgWin Window{1c292b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7105): LgDataFeature() Constructor: none
,D/LgDataFeature( 7105): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
,W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@138df27b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1033): Displayed com.test.thalitest/.MainActivity: +687ms (total +783ms)
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{3572bcf9 u0 com.test.thalitest/.MainActivity t4} time:277000
,I/Timeline( 7105): Timeline: Activity_idle id: android.os.BinderProxy@3fec10b3 time:277003
I/chromium( 7105): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7105): 
,D/JsMessageQueue( 7105): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7105): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7105): 
,D/jxcore_app_log( 7105): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434864512
,D/JX-Cordova( 7105): jxcore cordova android initializing
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 277704343648; DSPS: 9241154; Offset : -4329515589
E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
W/jxcore-log( 7105): Initializing JXcore engine
W/jxcore-log( 7105): JXcore engine is ready
W/jxcore-log( 7105): Starting JXcore engine
W/.test.thalitest( 7105): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8601]" dev="sockfs" ino=8601 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7105): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7105): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7395]" dev="sockfs" ino=7395 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7105): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7105): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32420]" dev="sockfs" ino=32420 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7105): Background sticky concurrent mark sweep GC freed 132262(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.637ms total 134.913ms
,W/jxcore-log( 7105): Platform android
W/jxcore-log( 7105): 
W/jxcore-log( 7105): Process ARCH arm
W/jxcore-log( 7105): 
,I/jxcore-log( 7105): JXcore Cordova bridge is ready!
I/jxcore-log( 7105): 
W/jxcore-log( 7105): JXcore engine is started
,I/jxcore-log( 7105): Toggling radios to true
I/jxcore-log( 7105): 
,D/BluetoothAdapter( 7105): enable(): BT is already enabled..!
D/WifiService( 1033): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1033): setWifiEnabled: true pid=7105, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1033): setWifiEnabled: true pid=7105, uid=10311
,E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1033): disconnect pid=7105, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1033): reconnect pid=7105, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1033):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7105): Radios toggled
I/jxcore-log( 7105): 
E/WifiNative: ( 1033): [279,717,441 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1033): doBoolean: DISCONNECT
I/jxcore-log( 7105): My device name is: LGE-LG-D855
I/jxcore-log( 7105): 
I/wpa_supplicant( 2683): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1033): DISCONNECT: returned true
E/WifiStateMachine( 1033): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1033): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1033): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1033): InitialState.processMessage what=4
D/Tethering( 1033): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1033): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
E/Netd    (  315): ifc_reset_connections failed on iface wlan0 for address 192.168.1.141/24 (Unknown error -1)
D/DhcpStateMachine( 1033): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager( 1033): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7159 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1033): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1033):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 1033): [279,858,312 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1033): doBoolean: RECONNECT
I/wpa_supplicant( 2683): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1033): RECONNECT: returned true
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1033):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279872
E/WifiStateMachine( 1033):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279872
D/LGWifiP2pService( 1033): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1033): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1033): disableDataServiceNotify
D/DSQN    ( 1033): stop dsqn bin
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1033): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/CSLegacyTypeTracker( 1033): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1033): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/WifiHS20( 1033): hidePasspointNotification off =false
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279897  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279897  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1033):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1033):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 10,33): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1033): Removing idletimer
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1033): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1033): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNetworkAgent( 1033): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1033):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279908  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279915  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1033): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateSCANNING
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7159): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7159): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7159): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7159): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7159): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7159): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1033): StoppedState
D/DhcpStateMachine( 1033): StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7159): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7159): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7159): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7159): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7159): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7159): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1033): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 6654:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10008/pid_6654/cgroup.procs: No such file or directory
,I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7192): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7159): LgDataFeature() Constructor: none
D/LgDataFeature( 7159): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
,I/ActivityManager( 1033): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7217 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1033): Killing 6114:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_6114/cgroup.procs: No such file or directory
,W/ResourcesManager( 7217): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7217): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7217): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7217): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7217): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7217): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7217): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7217): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7217): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7192): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7217): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7192): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7192): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7217): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7217): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7217): LgDataFeature() Constructor: none
D/LgDataFeature( 7217): LgDataFeature() Constructor Done, null
,V/SoundPool( 7217): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7217): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7217): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7217): doLoad: loading sample sampleID=1
I/QRemote ( 7217): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7217): Start decode
D/QRemote ( 7217): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6848): QS Service created
V/MediaPlayer[Native]( 7217): decode(31, 10857164, 17813)
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb54747c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
E/QRemote ( 7217): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6848): Service initServices...
D/UEI.SmartControl( 6848): QS start get config
V/LGMDMManager( 7217): Create singleton instance
,V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
,V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
,V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb54747c0, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb54747c0, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795744
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321),: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcdd0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb54747c0, 6, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab504000, 0xb57d2000, 4096)
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab505000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab506000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab507000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab508000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab509000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50a000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50b000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50c000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50d000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50e000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab50f000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab510000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab511000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab512000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab513000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab514000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab515000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab516000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab517000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab518000, 0xb57d2000, 4096)
,V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab519000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51a000, 0xb57d2000, 4096)
,V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51b000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51c000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51d000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51e000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab51f000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab520000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab521000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab522000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab523000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab524000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab525000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab526000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab527000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab528000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab529000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52a000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52b000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52c000, 0xb57d2000, 4096)
,V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52d000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52e000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab52f000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab530000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab531000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab532000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab533000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab534000, 0xb57d2000, 4096)
V/AudioCache(  321): write(0xb57d2000, 4096)
V/AudioCache(  321): memcpy(0xab535000, 0xb57d2000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb57d2000, 280)
V/AudioCache(  321): memcpy(0xab536000, 0xb57d2000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb54747c0, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb54747c0, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
,V/AudioCache(  321): notify(0xb54747c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcdd0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 7217): close(31)
V/SoundPool( 7217): pointer = 0x9fff7000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8218
,I/UEI.SmartControl( 6848): Supports setup maps: true
,D/UEI.SmartControl( 6848): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6848): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6848): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6848): ### init IR Blaster...
,D/serial_port( 6848): Configuring serial port
E/UEI.SmartControl( 6848): UEIBLaster setting for 616
I/UEI.SmartControl( 6848): Setting serial record hearder size = 2
I/UEI.SmartControl( 6848): configuring settings for MAXQ616
I/UEI.SmartControl( 6848): Get version...
D/UEI.SmartControl( 6848): serial port data available: 21
,D/UEI.SmartControl( 6848): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6848): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6848): QS saving settings...
D/UEI.SmartControl( 6848): IR Blaster version: 25672567
D/UEI.SmartControl( 6848): serial port data available: 4
,W/ContextImpl( 6848): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6848): Services init done
D/UEI.SmartControl( 6848): QS Service init finished
,D/UEI.SmartControl( 6848): QS Service version name: 2.1.91
D/UEI.SmartControl( 6848): QS Service version code: 201091
I/UEI.SmartControl( 6848): Device manager: loading config....
D/UEI.SmartControl( 6848): ----------- loading internal config...
,D/UEI.SmartControl( 6848): Service requested: Control
,E/UEI.SmartControl( 6848): Loading SETTINGS...
D/UEI.SmartControl( 6848): Request IControl service: devices are loaded...
I/QRemote ( 7217): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6848): ------ IControl API: 11
D/UEI.SmartControl( 6848): File observer start...
E/UEI.SmartControl( 6848): IR Port is disabled: false
D/UEI.SmartControl( 6848): Starting file observer...
I/UEI.SmartControl( 6848): Registering callback...
D/UEI.SmartControl( 6848): Internal service binding...
,I/UEI.SmartControl( 6848): ------ IControl API: 19
I/UEI.SmartControl( 6848): Registering Services Ready callback...
D/UEI.SmartControl( 6848): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6848): Notify AllClients services are ready: 0
,I/QRemote ( 7217): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7217): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7217): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6848): -----service ready thread exits
D/QRemote ( 7217): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7217): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6848): ------ IControl API: 8
D/QRemote ( 7217): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7217): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7217): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7217): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7217): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7217): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7217): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7217): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7217): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7217): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452863119447]
D/QRemote ( 7217): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1033): Killing 6139:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7217): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1033): failed to open /acct/uid_10019/pid_6139/cgroup.procs: No such file or directory
,V/QRemote ( 7217): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7217): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 7217): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1033): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1033): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2683): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1033):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1033):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1033):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1033):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,D/WifiNative-wlan0( 1033): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=282072  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=282089  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7217): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2683): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1033): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1033):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7159): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7159): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7159): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1033): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsControl( 7159): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7159): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7159): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7159): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=282180  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=282181  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2683): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2683): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1033): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1033): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1033): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1033):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282187
E/WifiStateMachine( 1033):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282187
E/WifiStateMachine( 1033):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:,ff:d4:d3:aa:48 Target=any roam=0 rt=282187
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282188
E/WifiStateMachine( 1033):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=282188
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=282189  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=282198  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=282199  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=282200  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1033):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=282201
E/WifiStateMachine( 1033):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=282201
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1033): doString: [STATUS]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1033):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1033): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
I/WifiServerServiceExt( 1033): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1033): setKeepAlivePacketInterval msec : 60
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/ConnectivityService( 1033): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1033): Got NetworkAgent Messenger
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1033): NetworkAgent connected
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1033): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1033): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1033): WaitBeforeStartState
E/WifiStateMachine( 1033):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=282259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=282259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=282260  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1033):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=282261  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=282261  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=282262  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1033):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
,D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1033): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 0
D/WifiNative-wlan0( 1033): SET ps 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 1: returned true
,D/LGWifiP2pService( 1033): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b38093c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b38093c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1033): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1033): DHCP Start wake lock is acquired.
E/WifiStateMachine( 1033): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1033): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1033): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1033): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1033):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1033):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1033):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2683): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1033): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
,D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1033):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1033): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1033): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1033): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1033): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
D/WifiHS20( 1033): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1033): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1033): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1033): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1033): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1033): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1033): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1033): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1033): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1033): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1033): currentScore = 0, newScore = 20
D/ConnectivityService( 1033):    accepting network in place of null
D/ConnectivityService( 1033): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1033): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1033): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1033): [e] list.add(nai) empty : false size,: 1
D/ConnectivityService( 1033): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1033): validation of new default Network = false
D/ConnectivityService( 1033): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1033): enableDataServiceNotify 
D/DSQN    ( 1033): start dsqn bin
D/TelephonyNetworkFactory-1( 1875): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1033): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1033): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
W/dsqn    ( 7288): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7288): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
E/DSQN    ( 7288): DSQN ssw
V/NetworkPolicy( 1033): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7217): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7217): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7217): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7217): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7192): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7192): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7159): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  315): argv[0]=dsqncommand
,D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1033): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1033): start to monitor internet connection
D/WiFiOffLoadBroadcast( 7159): MCCMNC not supported: null
D/QRemote ( 7217): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7217): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7217): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7217): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7217): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:05:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452863120568], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452863120547]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Validated
D/ConnectivityService( 1033): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1033): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1033): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1875): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1875):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1033): DHCPV4 request on wlan0
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
V/LgDhcpStateMachineHelper( 1033): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1033): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7294): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7294): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7294): version 5.5.6 starting
E/dhcpcd  ( 7294): get_duid: m
D/dhcpcd  ( 7294): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7294): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7294): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7294): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7294): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7294): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7294): wlan0: sending REQUEST (xid 0x9fc146b7), next in 3.46 seconds
,I/Choreographer( 7105): Skipped 187 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7105): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7105): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1033): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1033): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6616): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5449): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5449): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1033): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7311 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  345): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 34.946ms
,I/art     (  345): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 281us total 15.146ms
,I/art     (  345): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 282us total 14.842ms
,D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7311): onCreate
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
,D/LgDataFeature( 7311): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@feaa479
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7311): begin check event
I/AppUp4:CustModeStarterReceiver( 7311): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7311): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7311): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7311): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7311): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1033): Killing 6682:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_6682/cgroup.procs: No such file or directory
,D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3330): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3330): DownloadService onCreate
,I/DownloadManager( 3330): in removeSpuriousFiles
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4314): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4314): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@12ffe8cd on behalf of 3330
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
,I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3330): in trimDatabase
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@3c97e493 on behalf of 3330
,I/ActivityManager( 1033): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7354 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3330): DownloadService onStartCommand
V/DownloadManager( 3330): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@18af44c9 on behalf of 3330
V/DownloadManager( 3330): processing inserted download 1
V/DownloadManager( 3330): processing inserted download 4
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3330): processing inserted download 7
E/LGDMClient( 4314): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4314): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4314): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3330): processing inserted download 8
V/DownloadManager( 3330): processing inserted download 9
,V/DownloadManager( 3330): processing inserted download 10
V/DownloadManager( 3330): processing inserted download 16
V/DownloadManager( 3330): processing inserted download 17
V/DownloadManager( 3330): processing inserted download 18
,V/DownloadManager( 3330): processing inserted download 21
V/DownloadManager( 3330): DownloadService onDestroy
,W/ResourcesManager( 7354): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7354): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7354): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7354): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7354): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7354): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7354): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7354): LgDataFeature() Constructor: none
D/LgDataFeature( 7354): LgDataFeature() Constructor Done, null
,D/eas_req ( 7354): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1033): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7383 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7354): JNI_OnLoad()
I/HubEmail( 7354): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7354): registerNatives()
I/HubEmail( 7354): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7354): registerNativeMethods()
I/HubEmail( 7354): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7354): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1033): Killing 6709:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup( 1033): failed to open /acct/uid_10027/pid_6709/cgroup.procs: No such file or directory
W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3265): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3265): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3265): networkInfo.isConnected() = false
,I/ActivityManager( 1033): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7411 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7294): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
E/WifiStateMachine( 1033):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7294): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7294): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7294): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7294): wlan0: adding default route via 192.168.1.1
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/dhcpcd  ( 7294): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/dhcpcd  ( 7294): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7294): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7294): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1033): identical MTU - not setting
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1033): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
,V/FormManager( 7383): There are no updated forms. The schedule will be deleted.
,I/ActivityManager( 1033): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7441 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 6733:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,V/FormManager( 7383): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1033): failed to open /acct/uid_10061/pid_6733/cgroup.procs: No such file or directory
I/ActivityManager( 1033): Killing 6794:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1033): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7470 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1033): failed to open /acct/uid_10080/pid_6794/cgroup.procs: No such file or directory
D/DhcpStateMachine( 1033): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1033): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1033): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1033): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1033): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1033): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1033): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1033): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1033): RunningState
I/ActivityManager( 1033): Killing 6877:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6877/cgroup.procs: No such file or directory
,I/art     ( 7470): Almond Protected OAT
,D/WeatherApplication( 7470): removeAccount
,D/WeatherApplication( 7470): Account.length = 0
E/WeatherApplication( 7470): OPERATOR:OPEN
D/WeatherAncestor( 7470): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:22
D/Weather.Utils( 7470): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7470): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7470): 2 : This is isUpdating : false
D/WeatherAncestor( 7470): connectivity changed - connection : true
D/WeatherService( 7470): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7470): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7470): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7470): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7470): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7470): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:22
,E/WifiStateMachine( 1033):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1033):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1033):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1033):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1033):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/ActivityManager( 1033): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7488 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 6896:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6896/cgroup.procs: No such file or directory
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7488): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
V/WifiInternetCheck( 1033): Single check msg out of sync, ignoring.
I/LibraryLoader( 7488): Loading: webviewchromium
I/LibraryLoader( 7488): Time to load native libraries: 5 ms (timestamps 5365-5370)
I/LibraryLoader( 7488): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7488): Binding Chromium to main looper Looper (main, tid 1) {f200388}
I/LibraryLoader( 7488): Expected native library version number "",actual native library version number ""
I/chromium( 7488): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1033): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/BrowserStartupController( 7488): Initializing chromium process, renderers=0
W/art     ( 7488): Attempt to remove local handle scope entry from IRT, ignoring
D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5449): type=WIFI subType= reason=null isConnected=true
,W/chromium( 7488): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7488): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7488): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb14fd700, uid 10093
W/AudioManagerAndroid( 7488): Requires BLUETOOTH permission
I/Adreno-EGL( 7488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7488): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7488): Build Date: 12/12/14 금
I/Adreno-EGL( 7488): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7488): Remote Branch: 
I/Adreno-EGL( 7488): Local Patches: 
I/Adreno-EGL( 7488): Reconstruct Branch: 
,I/NSApplication( 7488): Starting up...
,I/ActivityManager( 1033): Killing 6925:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10005/pid_6925/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ContextImpl( 6616): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7311): onReceive
,D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@feaa479
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7311): begin check event
I/AppUp4:CustModeStarterReceiver( 7311): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3330): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3330): DownloadService onCreate
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4314): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3330): in removeSpuriousFiles
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4314): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@3c5236ef on behalf of 3330
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3330): in trimDatabase
I/LgeMiscReceiver( 3265): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3265): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3265): networkInfo.isConnected() = false
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3330): DownloadService onStartCommand
,V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@2f82da on behalf of 3330
V/DownloadManager( 3330): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@1cb5530b on behalf of 3330
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4314): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4314): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4314): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7470): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:23
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3330): processing inserted download 1
V/DownloadManager( 3330): processing inserted download 4
V/DownloadManager( 3330): processing inserted download 7
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
,V/DownloadManager( 3330): processing inserted download 8
D/Weather.Utils( 7470): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7470): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7470): 2 : This is isUpdating : false
D/WeatherAncestor( 7470): connectivity changed - connection : true
D/WeatherService( 7470): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@89c561f
W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/ForecastDataCache( 7470): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7470): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7470): 2 : Cache is up-to-date, count: 0
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/Weather_cast( 7470): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7470): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:23
V/DownloadManager( 3330): processing inserted download 9
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
V/DownloadManager( 3330): processing inserted download 10
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,V/DownloadManager( 3330): processing inserted download 16
,V/DownloadManager( 3330): processing inserted download 17
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
V/DownloadManager( 3330): processing inserted download 18
V/DownloadManager( 3330): processing inserted download 21
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3330): DownloadService onDestroy
,D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7383): There are no updated forms. The schedule will be deleted.
V/FormManager( 7383): Alarm would be updated, because LastCheckTime has been updated.
D/PostponalbeReceiver( 6616): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6616): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7311): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7311): onReceive
D/AppUp4:CustFacade( 7311): Context : android.app.ReceiverRestrictedContext@feaa479
D/AppUp4:CustFacade( 7311): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7311): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7311): begin check event
I/AppUp4:CustModeStarterReceiver( 7311): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3330): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4314): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3330): DownloadService onCreate
I/LGDMClient( 4314): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4314): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3330): in removeSpuriousFiles
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3330): DownloadService onStartCommand
V/DownloadManager( 3330): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3265): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3265): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3265): networkInfo.isConnected() = true
D/PhoneState( 3265): setPdpRejectCasuse : false
E/LGDMClient( 4314): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4314): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4314): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7470): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:24
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/Weather.Utils( 7470): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7470): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7470): 2 : This is isUpdating : false
D/WeatherAncestor( 7470): connectivity changed - connection : true
D/WeatherService( 7470): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@89c561f
D/ForecastDataCache( 7470): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7470): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7470): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7470): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7470): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:5:24
I/art     ( 2135): Explicit concurrent mark sweep GC freed 37310(2MB) AllocSpace objects, 11(1456KB) LOS objects, 51% free, 30MB/62MB, paused 1.522ms total 60.376ms
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,V/FormManager( 7383): There are no updated forms. The schedule will be deleted.
D/ChimeraCfgMgr( 2366): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
V/FormManager( 7383): Alarm would be updated, because LastCheckTime has been updated.
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
V/QRemote ( 7217): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7217): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8218
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
D/QuickStatusbarLayout( 1421): Notification difference=198
,D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/art     ( 1033): Explicit concurrent mark sweep GC freed 85591(4MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/67MB, paused 1.929ms total 142.333ms
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@1ee414e7 on behalf of 3330
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3330): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3330): in trimDatabase
V/DownloadManager( 3330): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@37257894 on behalf of 3330
D/LgeQuickCoverNLService( 1421): onNotificationPosted
V/DownloadManager( 3330): created cursor android.database.sqlite.SQLiteCursor@3c299f3d on behalf of 3330
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/Kids    ( 2366): [AccountUtils] Account not ready
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
V/DownloadManager( 3330): processing inserted download 1
V/DownloadManager( 3330): processing inserted download 4
V/DownloadManager( 3330): processing inserted download 7
V/DownloadManager( 3330): processing inserted download 8
V/DownloadManager( 3330): processing inserted download 9
V/DownloadManager( 3330): processing inserted download 10
V/DownloadManager( 3330): processing inserted download 16
V/DownloadManager( 3330): processing inserted download 17
,V/DownloadManager( 3330): processing inserted download 18
V/DownloadManager( 3330): processing inserted download 21
D/QuickStatusbarLayout( 1421): Notification difference=198
V/DownloadManager( 3330): DownloadService onDestroy
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/UEI.SmartControl( 6848): Internal timer expired: 4
D/UEI.SmartControl( 6848): unbind internal service
,D/serial_port( 6848): close(fd = 24)
,I/UEI.SmartControl( 6848): Serial port is closed.
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1033): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7488): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 297706409578; DSPS: 9896582; Offset : -4329525010
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{839f5cc type 2 when 303163 android} when 303163
,I/BooksSync( 6999): Starting books sync
,D/BooksSync( 6999): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5598964533879562441&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
,W/ApiaryClient( 6999): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5598964533879562441&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5598964533879562441&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,E/BooksSync( 6999): Soft error: 
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5598964533879562441&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
E/BooksSync( 6999): Sync error
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5598964533879562441&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
I/BooksSync( 6999): Finished books sync
,D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 303163, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 317708033997; DSPS: 10551995; Offset : -4329517659
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
E/WifiStateMachine( 1033):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1033):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1033):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2c83556 type 2 when 333219 android} when 333219
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 337709887740; DSPS: 11207416; Offset : -4329525697
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 357712076326; DSPS: 11862847; Offset : -4329503727
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6249): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6249): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6249): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6249): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6249): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6249): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 377713943245; DSPS: 12518269; Offset : -4329528977
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 397715718863; DSPS: 13173687; Offset : -4329523274
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 417717253543; DSPS: 13829097; Offset : -4329514630
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 437718779264; DSPS: 14484507; Offset : -4329514892
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 457720410871; DSPS: 15139921; Offset : -4329530998
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 477722211385; DSPS: 15795340; Offset : -4329531178
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 497723719189; DSPS: 16450749; Offset : -4329518580
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 517725373036; DSPS: 17106163; Offset : -4329513020
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 537726867039; DSPS: 17761572; Offset : -4329514222
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 557728383177; DSPS: 18416982; Offset : -4329523729
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{3eabc48 type 2 when 558592 android} when 558592
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,I/BooksSync( 6999): Starting books sync
,D/BooksSync( 6999): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8940294563087581467&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
,W/ApiaryClient( 6999): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8940294563087581467&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8940294563087581467&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
E/BooksSync( 6999): Soft error: 
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8940294563087581467&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
,E/BooksSync( 6999): Sync error
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8940294563087581467&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
I/BooksSync( 6999): Finished books sync
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 558592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 577729978481; DSPS: 19072394; Offset : -4329515547
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{1a52e5f2 type 2 when 588780 android} when 588780
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 597731656652; DSPS: 19727809; Offset : -4329515843
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 617733435654; DSPS: 20383227; Offset : -4329506888
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 637735193510; DSPS: 21038645; Offset : -4329519103
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 657737007045; DSPS: 21694064; Offset : -4329505922
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 677738556100; DSPS: 22349475; Offset : -4329513368
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 697740734946; DSPS: 23004907; Offset : -4329531683
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 717742286554; DSPS: 23660317; Offset : -4329505954
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1033): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3768): Disconnected process message: 10, size: 0
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 737744168213; DSPS: 24315739; Offset : -4329516463
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 757745653568; DSPS: 24971148; Offset : -4329526391
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 777747144759; DSPS: 25626557; Offset : -4329530588
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 797748940585; DSPS: 26281976; Offset : -4329535378
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 817750689536; DSPS: 26937393; Offset : -4329525694
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 837752181873; DSPS: 27592802; Offset : -4329529004
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 857754046447; DSPS: 28248223; Offset : -4329525898
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,I/ActivityManager( 1033): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7705 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7705): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7705): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3432472
I/ActivityManager( 1033): Killing 6249:com.android.vending/u0a44 (adj 15): empty #17
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
W/libprocessgroup( 1033): failed to open /acct/uid_10044/pid_6249/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 877756610919; DSPS: 28903667; Offset : -4329524747
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 897758180286; DSPS: 29559078; Offset : -4329511776
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 917759899966; DSPS: 30214495; Offset : -4329531519
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 937762051052; DSPS: 30869925; Offset : -4329517029
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{287d443 type 2 when 941654 com.android.bluetooth} when 941654
,W/bt-smp  ( 3768): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3768): Plain text(LSB ~ MSB) = ee 70 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3768): Encrypted text(LSB ~ MSB) = 0b 42 4c 44 0e db 18 7f 65 1b 85 b8 33 c1 44 3a 
W/bt-btm  ( 3768): Stopping oneshot timer
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 957763852660; DSPS: 31525344; Offset : -4329515776
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 977765406298; DSPS: 32180755; Offset : -4329518404
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 997766912696; DSPS: 32836164; Offset : -4329507446
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1017768435137; DSPS: 33491574; Offset : -4329511092
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1037771098358; DSPS: 34147021; Offset : -4329502640
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1057772615121; DSPS: 34802431; Offset : -4329511782
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2553fac0 type 2 when 1065551 android} when 1065551
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,I/BooksSync( 6999): Starting books sync
,D/BooksSync( 6999): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1033): Explicit concurrent mark sweep GC freed 35069(1594KB) AllocSpace objects, 12(1344KB) LOS objects, 33% free, 44MB/66MB, paused 2.231ms total 74.702ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4903444430123539012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4903444430123539012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4903444430123539012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,E/BooksSync( 6999): Soft error: 
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4903444430123539012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
E/BooksSync( 6999): Sync error
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4903444430123539012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
I/BooksSync( 6999): Finished books sync
,D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1065551, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1033): battery changed pluggedType: 2
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3768): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1077777807926; DSPS: 35457961; Offset : -4329507303
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{11372caa type 2 when 1096313 android} when 1096313
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1097779402033; DSPS: 36113374; Offset : -4329530290
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1117781783015; DSPS: 36768812; Offset : -4329529783
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1137783306654; DSPS: 37424222; Offset : -4329531997
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1157784827010; DSPS: 38079631; Offset : -4329506976
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1177786362003; DSPS: 38735042; Offset : -4329528562
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1197787854807; DSPS: 39390451; Offset : -4329531224
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1217789518549; DSPS: 40045865; Offset : -4329515274
,I/UsageStatsService( 1033): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{1996009b type 2 when 962492 com.google.android.gms} when 962492
V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{2befac38 type 0 when 1452864010208 com.google.android.gms} when 1452864010208
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,I/EventLogService( 2366): Aggregate from 1452862210132 (log), 1452862210132 (data)
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1237792012345; DSPS: 40701307; Offset : -4329523816
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1257793520097; DSPS: 41356716; Offset : -4329511660
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1277795027954; DSPS: 42012126; Offset : -4329529474
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1297796759717; DSPS: 42667542; Offset : -4329506746
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,W/GCM     ( 2135): Heartbeat timeout, GCM connection reset -11816
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{256e604d type 2 when 1297366 com.google.android.gms} when 1297366
D/ConnectivityService( 1033): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Checking http://clients3.google.com/generate_204 on "NG700"
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:22:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452864147414], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452864147397]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Validated
D/ConnectivityService( 1033): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1033): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1033): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{1ec9e813 type 2 when 1317092 com.google.android.gms} when 1317092
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2135): Connected
,D/GCM     ( 2135): Message class com.google.f.a.a.p
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1317798355699; DSPS: 43322955; Offset : -4329527935
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1337799909962; DSPS: 43978366; Offset : -4329530251
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1357802265528; DSPS: 44633803; Offset : -4329524487
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1377803805729; DSPS: 45289213; Offset : -4329510217
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1397805621398; DSPS: 45944633; Offset : -4329525524
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1417807157328; DSPS: 46600043; Offset : -4329515369
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1437808610809; DSPS: 47255451; Offset : -4329526862
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1457810753459; DSPS: 47910881; Offset : -4329520365
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1477812264388; DSPS: 48566290; Offset : -4329505005
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1497813766360; DSPS: 49221700; Offset : -4329528809
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1517815384634; DSPS: 49877113; Offset : -4329528199
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1537816870095; DSPS: 50532521; Offset : -4329507452
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1557818366806; DSPS: 51187930; Offset : -4329505843
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1577819873725; DSPS: 51843340; Offset : -4329525114
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1597822165488; DSPS: 52498775; Offset : -4329522118
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1617823695377; DSPS: 53154185; Offset : -4329518056
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1637825166046; DSPS: 53809593; Offset : -4329512412
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
D/WifiController( 1033): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3768): Disconnected process message: 10, size: 0
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1657826788018; DSPS: 54465006; Offset : -4329507847
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1677828319833; DSPS: 55120416; Offset : -4329501519
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1697830706076; DSPS: 55775855; Offset : -4329526478
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1717832241641; DSPS: 56431265; Offset : -4329516610
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1737833730592; DSPS: 57086674; Offset : -4329523046
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1757835345427; DSPS: 57742087; Offset : -4329525722
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7705): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7705): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3432472
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1777836947295; DSPS: 58397499; Offset : -4329510819
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1797838708849; DSPS: 59052917; Offset : -4329519154
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1817840879102; DSPS: 59708348; Offset : -4329515832
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1837842388210; DSPS: 60363758; Offset : -4329532550
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,W/bt-smp  ( 3768): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3768): Plain text(LSB ~ MSB) = e5 00 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3768): Encrypted text(LSB ~ MSB) = b7 37 b8 ef 24 d9 bd 0f eb 63 e5 f1 ea c8 94 c8 
,W/bt-btm  ( 3768): Stopping oneshot timer
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2c4db449 type 2 when 1841682 com.android.bluetooth} when 1841682
I/ProcessStatsService( 1033): Prepared write state in 17ms
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,I/ProcessStatsService( 1033): Prepared write state in 9ms
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,I/ProcessStatsService( 1033): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-30-01.bin
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1857843949712; DSPS: 61019169; Offset : -4329527367
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1877845481007; DSPS: 61674579; Offset : -4329522184
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1897847013655; DSPS: 62329989; Offset : -4329515286
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1917848719741; DSPS: 62985405; Offset : -4329518002
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1937850867338; DSPS: 63640835; Offset : -4329506557
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1957852788685; DSPS: 64296258; Offset : -4329507792
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1977854277946; DSPS: 64951667; Offset : -4329514126
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1997855757680; DSPS: 65607076; Offset : -4329529727
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 2017857286369; DSPS: 66262486; Offset : -4329526943
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 2037858770581; DSPS: 66917894; Offset : -4329507575
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 2057862117813; DSPS: 67573364; Offset : -4329517356
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=85640895, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{37a314e type 2 when 2076122 android} when 2076122
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=85640895 [*alarm*], flags=0x0
,I/BooksSync( 6999): Starting books sync
,D/BooksSync( 6999): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1202580469702525653&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 2077863806763; DSPS: 68228779; Offset : -4329506481
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
,W/ApiaryClient( 6999): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1202580469702525653&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 39762(2MB) AllocSpace objects, 30(4MB) LOS objects, 51% free, 30MB/62MB, paused 2.307ms total 63.857ms
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/BooksAccountManager( 6999): Authentication error
E/BooksAccountManager( 6999): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6999): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6999): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6999): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6999): null auth token
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1125c401 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6999): Error response from books API: {
W/ApiaryClient( 6999):  "error": {
W/ApiaryClient( 6999):   "errors": [
W/ApiaryClient( 6999):    {
W/ApiaryClient( 6999):     "domain": "global",
W/ApiaryClient( 6999):     "reason": "required",
W/ApiaryClient( 6999):     "message": "Login Required",
W/ApiaryClient( 6999):     "locationType": "header",
W/ApiaryClient( 6999):     "location": "Authorization"
W/ApiaryClient( 6999):    }
W/ApiaryClient( 6999):   ],
W/ApiaryClient( 6999):   "code": 401,
W/ApiaryClient( 6999):   "message": "Login Required"
W/ApiaryClient( 6999):  }
W/ApiaryClient( 6999): }
W/ApiaryClient( 6999): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1202580469702525653&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6999): Headers:
W/ApiaryClient( 6999): accept-encoding: [gzip]
W/ApiaryClient( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6999): gdata-version: 2
,E/BooksSync( 6999): Soft error: 
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1202580469702525653&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {,
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more
,E/BooksSync( 6999): Sync error
E/BooksSync( 6999): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6999): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1202580469702525653&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6999): Headers:
E/BooksSync( 6999): accept-encoding: [gzip]
E/BooksSync( 6999): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6999): gdata-version: 2
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6999): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6999): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6999): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/BooksSync( 6999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6999): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6999): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6999): {
E/BooksSync( 6999):  "error": {
E/BooksSync( 6999):   "errors": [
E/BooksSync( 6999):    {
E/BooksSync( 6999):     "domain": "global",
E/BooksSync( 6999):     "reason": "required",
E/BooksSync( 6999):     "message": "Login Required",
E/BooksSync( 6999):     "locationType": "header",
E/BooksSync( 6999):     "location": "Authorization"
E/BooksSync( 6999):    }
E/BooksSync( 6999):   ],
E/BooksSync( 6999):   "code": 401,
E/BooksSync( 6999):   "message": "Login Required"
E/BooksSync( 6999):  }
E/BooksSync( 6999): }
E/BooksSync( 6999): 
E/BooksSync( 6999): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6999): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6999): 	... 8 more,
,I/BooksSync( 6999): Finished books sync
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2076122, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 2097865896444; DSPS: 68884208; Offset : -4329522695
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager( 1033): Killing 7411:com.android.chrome/u0a57 (adj 15): empty for 1820s
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{83d9674 type 2 when 2106894 android} when 2106894
I/ActivityManager( 1033): Killing 6616:com.wsandroid.suite.lge/1000 (adj 15): empty for 1820s
I/ActivityManager( 1033): Killing 7383:com.lge.formmanager/u0a26 (adj 15): empty for 1820s
I/ActivityManager( 1033): Killing 7354:com.lge.email/u0a23 (adj 15): empty for 1820s
I/ActivityManager( 1033): Killing 7311:com.lge.appbox.client/u0a11 (adj 15): empty for 1821s
I/ActivityManager( 1033): Killing 7159:com.android.settings/1000 (adj 15): empty for 1824s
I/ActivityManager( 1033): Killing 7192:com.lge.sync/1000 (adj 15): empty for 1824s
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6616/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_10026/pid_7383/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_7354/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_7311/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_7159/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_7192/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_10057/pid_7411/cgroup.procs: No such file or directory
D/AndroidRuntime( 7962): 
D/AndroidRuntime( 7962): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7962): CheckJNI is OFF
D/AndroidRuntime( 7962): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1033): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1033): Killing 7105:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1033): WIN DEATH: Window{1c292b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1033): Client connection lost with reason: 4
D/InputDispatcher( 1033): Window went away: Window{1c292b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1033): Skipping PackageSetting{3e33ea91 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{3572bcf9 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  341): DFP En is all cleared set to be enabled
W/ActivityManager( 1033): Spurious death for ProcessRecord{17c8979d 7105:com.test.thalitest/u0a311}, curProc for 7105: null
I/ActivityManager( 1033): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{3572bcf9 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1033): Duplicate finish request for ActivityRecord{3572bcf9 u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2091): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{3b1b6289 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2091): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2091): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{1a4e28e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1840): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2046): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3715): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/art     ( 4579): Explicit concurrent mark sweep GC freed 16944(945KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 513us total 65.765ms
W/System.err( 4533): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4533): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4533): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4533): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4533): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4533): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4533): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4533): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4533): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4533): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4533): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4533): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1033): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7994 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1926): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2091): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LIA_Informant_ActionManagerMessageHandler( 3715): handleMessage: what(1000) actionID(0x1000003)
I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8010 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2091): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2091): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1926): notifyUserLog: 1000004
V/BoardContentProvider( 3715): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 3715): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2091): , create_time: 1430558575574
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2091): , create_time: 1430558575600
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2091): , create_time: 1452774039338
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
D/WallpaperManager( 2091): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@138df27b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2091): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 1033): Explicit concurrent mark sweep GC freed 40756(2MB) AllocSpace objects, 18(1201KB) LOS objects, 33% free, 44MB/66MB, paused 2.166ms total 206.154ms
I/art     ( 1033): WaitForGcToComplete blocked for 52.236ms for cause Explicit
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
D/SplitUIManager( 1892): split_name #11 / not available #0
D/SplitUIService( 1892): removed split : 
I/LockScreenSettings( 8010): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/[LGHome]EVENT( 2091): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 7994): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ActivityManager( 1033): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/SplitUIManager( 1892): split_name #11 / not available #0
I/SplitUIService( 1892): split app #11
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] [-] updateMediaPlayerInfo
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): handleShortcutListChanged...
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/administrator( 1033): Handling package changes for user 0
I/ActivityManager( 1033): Killing 7441:com.lge.drmservice/u0a62 (adj 15): empty for 1824s
D/PluginManager( 7994): init()
I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3189): Thermal-Lib-Client: Client request sent
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/NotificationService( 1033): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1033): Receieved: android.intent.action.PACKAGE_REMOVED
I/[Concierge]WidgetView( 2091): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1469): handleShortcutListChanged...
W/libprocessgroup( 1033): failed to open /acct/uid_10062/pid_7441/cgroup.procs: No such file or directory
I/art     ( 1033): Explicit concurrent mark sweep GC freed 9641(541KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.420ms total 186.019ms
D/[Concierge]Service( 2591): onStartCommand(). Type : 8
D/[Concierge]Service( 2591): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2091): change position of spinner
D/[Concierge]Service( 2591): Update widget ID : 11
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{4a04b89 u0 com.lge.launcher2/.Launcher t3} time:2110681
D/TaskPersister( 1033): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2591): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2091): initWebView(). Time : 1452864948748
I/[Concierge]WebView( 2091): Return exist ConciergeWebView. Reuse : 809336530
D/[Concierge]WidgetView( 2091): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2091): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e9f3819
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2091): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2091): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2091): Widget kill message received. Destory myself. My : 1452862866370, New one : 1452864948748
D/[Concierge]WidgetView( 2091): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2091): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7962): Shutting down VM
I/Timeline( 2091): Timeline: Activity_idle id: android.os.BinderProxy@16357330 time:2110790
W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2091): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ExternalStrings( 7994): load override strings
W/ExternalStrings( 7994): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7994): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7994): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7994): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7994): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7994): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7994): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7994): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7994): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7994): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7994): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7994): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7994): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7994): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7994): onCreate
I/chromium( 2091): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/Signer  ( 7994): override build config not found
D/Signer  ( 7994): value of property debug is false
I/GBoardtInterface( 2091): onReloaded()
I/GBoardWebViewClient( 2091): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3715): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3715): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1926): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3715): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3715): onEvent() : ACTION_BOARD_ENABLED
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7994): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
D/ActionManagerService( 1926): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3715): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3715): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3715): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3715): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3715): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
V/LGMDMManager( 7994): Create singleton instance
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 7994): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 7994): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7994): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1033): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8046 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 7470:com.lge.sizechangable.weather/u0a85 (adj 15): empty for 1825s
W/ActivityThread( 7994): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1033): failed to open /acct/uid_10085/pid_7470/cgroup.procs: No such file or directory

```
