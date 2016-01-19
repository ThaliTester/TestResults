#### Test 565307121a686b7_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 278084229996; DSPS: 9253100; Offset : -4312467775
,D/AndroidRuntime( 6505): 
D/AndroidRuntime( 6505): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6505): CheckJNI is OFF
D/AndroidRuntime( 6505): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1937): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{4c92521 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{4c92521 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6520 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6505): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1848): Display #0 changed.
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{28235727 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{2ac42dd4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6520): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6520): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6520): Loading: webviewchromium
I/LibraryLoader( 6520): Time to load native libraries: 3 ms (timestamps 7931-7934)
I/LibraryLoader( 6520): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6520): Binding Chromium to main looper Looper (main, tid 1) {27fc5f16}
,I/LibraryLoader( 6520): Expected native library version number "",actual native library version number ""
I/chromium( 6520): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6520): Initializing chromium process, renderers=0
,W/art     ( 6520): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6520): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  321): registerClient() client 0xb165cd80, uid 10311
,W/chromium( 6520): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6520): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6520): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20be70a3:true
I/Adreno-EGL( 6520): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6520): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6520): Build Date: 12/12/14 금
I/Adreno-EGL( 6520): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6520): Remote Branch: 
I/Adreno-EGL( 6520): Local Patches: 
I/Adreno-EGL( 6520): Reconstruct Branch: 
W/chromium( 6520): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6520): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6520): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6520): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6520): CordovaWebView is running on device made by: LGE
W/art     ( 6520): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6520): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6520): Render dirty regions requested: true
I/OpenGLRenderer( 6520): Initialized EGL, version 1.4
D/OpenGLRenderer( 6520): Enabling debug mode 0
D/Atlas   ( 6520): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{13fc2885 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6520): LgDataFeature() Constructor: none
D/LgDataFeature( 6520): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1470): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33892e89,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +583ms (total +679ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{2b7b0d46 u0 com.test.thalitest/.MainActivity t4} time:288380
I/Timeline( 6520): Timeline: Activity_idle id: android.os.BinderProxy@3468b9c6 time:288390
I/chromium( 6520): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6520): 
D/JsMessageQueue( 6520): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6520): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6520): 
D/jxcore_app_log( 6520): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434851968
I/chromium( 6520): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  341): DFP En is all cleared set to be enabled
,E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
W/jxcore-log( 6520): Initializing JXcore engine
W/jxcore-log( 6520): JXcore engine is ready
,W/Thread-723( 6595): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8407]" dev="sockfs" ino=8407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-723( 6595): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-723( 6595): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9982]" dev="sockfs" ino=9982 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-723( 6595): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/Thread-723( 6595): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[32186]" dev="sockfs" ino=32186 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6520): Starting JXcore engine
,I/art     ( 6520): Background sticky concurrent mark sweep GC freed 134739(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.293ms total 168.479ms
,W/jxcore-log( 6520): Platform android
W/jxcore-log( 6520): 
W/jxcore-log( 6520): Process ARCH arm
W/jxcore-log( 6520): 
,I/jxcore-log( 6520): JXcore Cordova bridge is ready!
I/jxcore-log( 6520): 
W/jxcore-log( 6520): JXcore engine is started
,I/jxcore-log( 6520): Toggling radios to true
I/jxcore-log( 6520): 
,D/BluetoothAdapter( 6520): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6520, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6520, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6520, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=6520, uid=10311, packageName=com.test.thalitest
,I/jxcore-log( 6520): Radios toggled
I/jxcore-log( 6520): 
,E/WifiStateMachine( 1037):  DisconnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6520): My device name is: LGE-LG-D855
I/jxcore-log( 6520): 
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1037): setLastSelectedConfiguration -1
E/WifiNative: ( 1037): [291,795,293 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
D/Tethering( 1037): InitialState.processMessage what=4
E/WifiStateMachine( 1037):  DisconnectedState CMD_RECONNECT 0 0
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [291,846,898 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1037):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=291856
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=291856  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6611 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=291903  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=291910  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=291911  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6611): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6611): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6611): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6611): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6611): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6611): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6611): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6611): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6611): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6611): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6611): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6637 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6002:com.android.defcontainer/u0a4 (adj 15): empty #17
I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 24.917ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 712us total 20.484ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 18.411ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6002/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6611): LgDataFeature() Constructor: none
D/LgDataFeature( 6611): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
,I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6657 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6153:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6153/cgroup.procs: No such file or directory
,W/ResourcesManager( 6657): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6657): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6657): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6657): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6657): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6657): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6657): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6657): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6657): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 6657): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6637): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6637): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6637): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6657): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6657): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6657): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6657): LgDataFeature() Constructor: none
D/LgDataFeature( 6657): LgDataFeature() Constructor Done, null
,V/SoundPool( 6657): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6657): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6657): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6657): doLoad: loading sample sampleID=1
I/QRemote ( 6657): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6657): Start decode
V/MediaPlayer[Native]( 6657): decode(31, 10857164, 17813)
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
V/AudioCache(  321): notify(0xb5474600, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
,V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6688 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6657): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
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
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
E/QRemote ( 6657): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
,V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port,
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcba0 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb5474600, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb5474600, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
,V/AwesomePlayer(  321): play_l() 
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
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796704
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb5474600, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab602000, 0xb57e2000, 4096)
V/LGMDMManager( 6657): Create singleton instance
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab603000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab604000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab605000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab606000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab607000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab608000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab609000, 0xb57e2000, 4096)
,V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60a000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60b000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60c000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60d000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60e000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab60f000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab610000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab611000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab612000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab613000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab614000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab615000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab616000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab617000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab618000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab619000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61a000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61b000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61c000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61d000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61e000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab61f000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab620000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab621000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab622000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab623000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab624000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab625000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab626000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab627000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab628000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab629000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62a000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62b000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62c000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62d000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62e000, 0xb57e2000, 4096)
,V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab62f000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab630000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab631000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab632000, 0xb57e2000, 4096)
V/AudioCache(  321): write(0xb57e2000, 4096)
V/AudioCache(  321): memcpy(0xab633000, 0xb57e2000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb57e2000, 280)
V/AudioCache(  321): memcpy(0xab634000, 0xb57e2000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb5474600, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb5474600, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb5474600, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
D/UEI.SmartControl( 6688): Quickset Services start...
I/UEI.SmartControl( 6688): Manufacture = LGE
D/UEI.SmartControl( 6688): Id = LGNevo
D/UEI.SmartControl( 6688): File observer start...
E/UEI.SmartControl( 6688): IR Port is disabled: false
D/UEI.SmartControl( 6688): Starting file observer...
,D/UEI.SmartControl( 6688): Extracting JNI libs...
D/UEI.SmartControl( 6688): --- this system supports 32-bit or 64-bit only
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
,V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 6657): close(31)
V/SoundPool( 6657): pointer = 0x9fff9000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4901
D/UEI.SmartControl( 6688): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6688): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6688): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6688): --- Selecting new region: 6
,I/UEI.SmartControl( 6688): Model = LG-D855
,D/UEI.SmartControl( 6688): QS Service created
I/UEI.SmartControl( 6688): Service initServices...
D/UEI.SmartControl( 6688): QS start get config
,D/UEI.SmartControl( 6688): Loading JNI Libs...
,I/UEI.SmartControl( 6688): Supports setup maps: true
D/UEI.SmartControl( 6688): QS start statue = true Error code = 0
I/UEI.SmartControl( 6688): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6688): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6688): ### init IR Blaster...
,D/serial_port( 6688): Configuring serial port
E/UEI.SmartControl( 6688): UEIBLaster setting for 616
I/UEI.SmartControl( 6688): Setting serial record hearder size = 2
I/UEI.SmartControl( 6688): configuring settings for MAXQ616
I/UEI.SmartControl( 6688): Get version...
D/UEI.SmartControl( 6688): serial port data available: 21
,D/UEI.SmartControl( 6688): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6688): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6688): QS saving settings...
D/UEI.SmartControl( 6688): IR Blaster version: 25672567
,D/UEI.SmartControl( 6688): serial port data available: 4
,I/UEI.SmartControl( 6688): Device manager: loading config....
,D/UEI.SmartControl( 6688): ----------- loading internal config...
W/ContextImpl( 6688): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6688): Services init done
D/UEI.SmartControl( 6688): QS Service init finished
D/UEI.SmartControl( 6688): QS Service version name: 2.1.91
D/UEI.SmartControl( 6688): QS Service version code: 201091
D/UEI.SmartControl( 6688): Service requested: Control
E/UEI.SmartControl( 6688): Loading SETTINGS...
,D/UEI.SmartControl( 6688): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6688): Internal service binding...
I/QRemote ( 6657): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6688): ------ IControl API: 11
I/UEI.SmartControl( 6688): Registering callback...
I/UEI.SmartControl( 6688): ------ IControl API: 19
I/UEI.SmartControl( 6688): Registering Services Ready callback...
D/UEI.SmartControl( 6688): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6688): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6688): -----service ready thread exits
I/QRemote ( 6657): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6657): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6657): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6657): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6657): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6688): ------ IControl API: 8
D/QRemote ( 6657): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6657): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6657): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6657): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 6657): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6657): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6657): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6657): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6657): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6657): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6657): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453241438855]
D/QRemote ( 6657): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 5590:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 6657): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1037): Killing 6185:com.google.android.partnersetup/u0a8 (adj 15): empty #18
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_5590/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6185/cgroup.procs: No such file or directory
V/QRemote ( 6657): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6657): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,I/wpa_supplicant( 2685): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3320 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3320 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3320 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3320 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=293987  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=294008  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2685): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=294087  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=294087  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294088
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294088
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294088
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294088
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=294088
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=294088  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6611): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6611): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6611): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=294096  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2685): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=294100  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=294100  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294101
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=294102
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6611): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6611): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6611): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6611): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  317): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 1
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=294170  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/DhcpStateMachine( 1037): StoppedState
,D/DhcpStateMachine( 1037): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=294171  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=294172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=294173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=294173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=294173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2685): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2685): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7d81c60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7d81c60 target=com.android.internal.util.StateMachine$SmHandler }
,V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.,
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6727): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6727): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6727): version 5.5.6 starting,
E/dhcpcd  ( 6727): get_duid: m
,D/dhcpcd  ( 6727): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 6727): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6727): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6727): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6727): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6727): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6727): wlan0: sending REQUEST (xid 0x9284fe8), next in 4.23 seconds
I/dhcpcd  ( 6727): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6727): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6727): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6727): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6727): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6727): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6727): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6727): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6727): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1037): RunningState
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2685): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1037): Adding iface wlan0 to network 100
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 1
,D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1037): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1848): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1848):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 28
,E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1037): requestTime failed
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocSvc_java( 1037): Sending msg: 10 arg1:0 arg2:1
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/dsqn    ( 6777): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6777): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/DSQN    ( 6777): DSQN ssw
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6657): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6637): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6637): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6657): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6657): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6657): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6637): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6637): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6611): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6611): MCCMNC not supported: null
D/QRemote ( 6657): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6657): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6657): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6657): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6657): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  317): argv[0]=dsqncommand
,D/LGDataListener(  317): argv[1]=wlan0
D/LGDataListener(  317): argv[2]=1
D/LGDataListener(  317): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 22:10:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453241441553], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453241441528]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1848): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1848):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6520): 
I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6520): 
I/jxcore-log( 6520): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6520): 
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 298085658952; DSPS: 9908507; Offset : -4312473067
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=153509566, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/QRemote ( 6657): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6657): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4901
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=153509566 [*alarm*], flags=0x0
,I/jxcore-log( 6520): Test app app.js loaded
I/jxcore-log( 6520): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6520): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6520): BLE advertisement is supported
I/jxcore-log( 6520): 
I/chromium( 6520): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/UEI.SmartControl( 6688): Internal timer expired: 1
,D/UEI.SmartControl( 6688): unbind internal service
,I/jxcore-log( 6520): --= Surplus to requirements =--
I/jxcore-log( 6520): 
I/jxcore-log( 6520): ****TEST TOOK:  ms ****
I/jxcore-log( 6520): 
I/jxcore-log( 6520): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6520): 
,D/serial_port( 6688): close(fd = 25)
,I/UEI.SmartControl( 6688): Serial port is closed.
D/AndroidRuntime( 6820): 
D/AndroidRuntime( 6820): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6820): CheckJNI is OFF
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 6136): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6136): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5340): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  317): res_queryN name = 2.android.pool.ntp.org succeed
,D/AndroidRuntime( 6820): Calling main entry com.android.commands.pm.Pm
D/AlarmManagerService( 1037): Setting time of day to sec=1453241444
W/AlarmManagerService( 1037): Unable to set rtc to 1453241444: Invalid argument
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6857 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/PackageSettings( 1037): Skipping PackageSetting{3f2c8505 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6520:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1037): WIN DEATH: Window{13fc2885 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{13fc2885 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2b7b0d46 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2b7b0d46 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{2b7b0d46 u0 com.test.thalitest/.MainActivity t4 f}
,I/AppUp4:AppBoxCP( 6857): onCreate
W/ActivityManager( 1037): Spurious death for ProcessRecord{167c3324 6520:com.test.thalitest/u0a311}, curProc for 6520: null
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 2029): [Launcher.java:5338:onStart()]onStart
W/AppUp4:DB( 6857):  [AppBoxDatabaseHelper] construct
I/[LGHome]EVENT( 2029): [Launcher.java:903:onResume()]onResume
,I/SecureClockService( 1937): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 3610): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 3610): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-19 23:10:44...... Request
I/LIA_Informant_Tips_LogTracer( 3610): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 149, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3610): DateInfo : SmartTips Total Working Day Count = 149
D/LIA_Informant_Tips_DateChangeManager( 3610): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 3610): DateInfo : Last Date Check Time = 2016-01-19 23:10:44
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
I/[SystemUI]Clock( 1470): onReceive = android.intent.action.TIME_SET
I/AppUp4:DB( 6857):  setFingerPrint start
I/AppUp4:DB( 6857):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/LgeClockWidgetControlView( 1470): time changed, timezoneChanged : false
I/AppUp4:DB( 6857):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6857):  SDK version = 21
I/AppUp4:DB( 6857):  beforefinger == newfinger no write in DB
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1813): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3610): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/[LGHome]EVENT( 2029): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{1764b7d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/AppUp4:AppBoxApplication( 6857): AppBoxApplication onCreate()
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{a0c6a72 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/NetworkStateForAutoUpdateMonitor( 6857): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6857): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6857): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6857): [onReceive] request level :IDLE....
I/art     ( 4392): Explicit concurrent mark sweep GC freed 24099(1439KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 472us total 95.378ms
,W/System.err( 4324): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4324): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4324): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4324): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4324): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4324): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4324): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4324): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4324): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4324): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1901): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3610): handleMessage: what(1000) actionID(0x1000003)
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]LGActivityUtil( 2029): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2029): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2029): [Launcher.java:1114:onPause()]onPause
,I/[SystemUI]QSlideListController( 1470): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1901): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3610): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3610): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/AppUp4:CustModeStarterReceiver( 6857): onReceive
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1470): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/SplitUIManager( 1865): split_name #11 / not available #0
D/SplitUIService( 1865): removed split : 
,D/SplitUIManager( 1865): split_name #11 / not available #0
I/SplitUIService( 1865): split app #11
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 60831(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.447ms total 187.668ms
,I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6879 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2029): , create_time: 1430558575574
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2029): , create_time: 1430558575600
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
,I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2029): , create_time: 1452774039338
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/art     ( 1037): WaitForGcToComplete blocked for 208.710ms for cause Explicit
D/LgDataFeature( 6857): LgDataFeature() Constructor: none
D/LgDataFeature( 6857): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6857): Context : android.app.ReceiverRestrictedContext@237e5284
D/AppUp4:CustFacade( 6857): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6857): isPhone : true
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33892e89,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2029): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/AppUp4:CustModeStarterReceiver( 6857): begin check event
I/AppUp4:CustModeStarterReceiver( 6857): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6857): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
W/ActivityManager( 1037): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2029): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=19 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 19
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
D/AppUp4:CustModeStarterReceiver( 6857): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6857): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6857): handleAsyncCustNotification do not startCustService
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 19
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/administrator( 1037): Handling package changes for user 0
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
,W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1470): createShortcutInfo...
D/LGDMClient( 4177): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4177): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ContextImpl( 4177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
D/LGDMClient( 4177): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/KeyguardModel( 1470): handleShortcutListChanged...
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
V/DownloadManager( 3381): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
V/DownloadManager( 3381): DownloadService onCreate
D/KeyguardModel( 1470): handleShortcutListChanged...
,I/DownloadManager( 3381): in removeSpuriousFiles
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/[LGHome]EVENT( 2029): [Launcher.java:5349:onStop()]onStop
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@2c1e8313 on behalf of 3381
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3381): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3381): in trimDatabase
V/DownloadManager( 3381): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@89fc950 on behalf of 3381
I/LGDMClient( 4177): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/eas_req ( 6221): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
W/ContextImpl( 4177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4177): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3381): DownloadService onStartCommand
V/DownloadManager( 3381): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3381): created cursor android.database.sqlite.SQLiteCursor@23e43d6f on behalf of 3381
D/LGDMClient( 4177): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4177): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4177): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4177): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3381): processing inserted download 1
V/DownloadManager( 3381): processing inserted download 4
V/DownloadManager( 3381): processing inserted download 7
V/DownloadManager( 3381): processing inserted download 8
V/DownloadManager( 3381): processing inserted download 9
V/DownloadManager( 3381): processing inserted download 10
V/DownloadManager( 3381): processing inserted download 16
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/DownloadManager( 3381): processing inserted download 17
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
V/DownloadManager( 3381): processing inserted download 18
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
,V/DownloadManager( 3381): processing inserted download 21
V/DownloadManager( 3381): processing inserted download 22
D/PhoneStatusBar( 1470): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6904 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     ( 1037): Explicit concurrent mark sweep GC freed 9095(529KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 14.895ms total 303.757ms
,I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1037): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6924 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[Concierge]WidgetView( 2029): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
V/DownloadManager( 3381): DownloadService onDestroy
,I/HubEmail( 6221): JNI_OnLoad()
I/HubEmail( 6221): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6221): registerNatives()
I/HubEmail( 6221): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6221): registerNativeMethods()
I/HubEmail( 6221): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6221): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{36b83310 u0 com.lge.launcher2/.Launcher t3} time:300295
,I/ReaderUtils( 6879): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/[Concierge]WidgetView( 2029): change position of spinner
D/[Concierge]Service( 2615): onStartCommand(). Type : 8
D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/[Concierge]Service( 2615): Update widget ID : 11
W/Settings( 6221): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[Concierge]WidgetView( 2029): initWebView(). Time : 1453241445366
W/Settings( 6221): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
E/GpsLocationProvider( 1037): No APN found to select.
,I/LgeMiscReceiver( 3321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3321): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3321): networkInfo.isConnected() = true
D/PhoneState( 3321): setPdpRejectCasuse : false
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = www.google.com, class = 1, type = 1
I/[Concierge]WebView( 2029): Return exist ConciergeWebView. Reuse : 443422084
D/[Concierge]WidgetView( 2029): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2029): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1a16b612
,I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/GAV2    ( 6879): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/DriveInitializer( 2375): Background init thread started
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2029): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2029): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2029): Widget kill message received. Destory myself. My : 1453241173542, New one : 1453241445366
D/[Concierge]WidgetView( 2029): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2029): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/VacuumService( 2119): Vacuum at: now=1453241445471 tag=VacuumService
D/libc-netbsd(  317): res_queryN name = www.google.com succeed
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/art     ( 2119): Explicit concurrent mark sweep GC freed 22295(1259KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.336ms total 41.649ms
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2375): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
E/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/BooksApp( 6879): Created application version: 3.2.35 (30235)
I/Timeline( 2029): Timeline: Activity_idle id: android.os.BinderProxy@384a6961 time:300476
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/GoogleURLConnFactory( 2119): Using platform SSLCertificateSocketFactory
,W/Uploader( 2119): No account for auth token provided
W/DriveInitializer( 2375): Background init thread ended
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/AndroidRuntime( 6820): Shutting down VM
,D/libc-netbsd(  317): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 6904): There are no updated forms. The schedule will be deleted.
V/FormManager( 6904): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6978 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/chromium( 2029): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/ActivityManager( 1037): Killing 5612:com.android.contacts/u0a19 (adj 15): empty #17
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/GBoardtInterface( 2029): onReloaded()
I/GBoardWebViewClient( 2029): onPageFinished url:file:///android_asset/www/main.html
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_5612/cgroup.procs: No such file or directory
,V/BoardContentProvider( 3610): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3610): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,W/Uploader( 2119): No account for auth token provided
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3610): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3610): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3610): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 3610): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3610): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3610): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3610): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,I/BooksSync( 6879): Starting books sync
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/DelayedSyncController( 6924): Delaying sync.
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
I/ActivityManager( 1037): Killing 6252:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DrmBroadcastReceiver( 6978): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6978): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6978): Service onCreate

```
