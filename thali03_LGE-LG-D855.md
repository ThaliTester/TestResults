#### Test 56449660311ec66_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 157856702862; DSPS: 5314744; Offset : -4351861381
,D/AndroidRuntime( 6336): 
D/AndroidRuntime( 6336): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6336): CheckJNI is OFF
D/AndroidRuntime( 6336): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1044): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1943): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1044): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1044): setTaskToReturnTo : TaskRecord{88cdf82 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1044): setTaskToReturnTo : TaskRecord{88cdf82 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1044): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1044): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6355 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6336): Shutting down VM
V/ActivityManager( 1044): Display changed displayId=0
D/DSDPConnection( 1855): Display #0 changed.
D/SplitWindowPolicy( 1943): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1943): topRunningActivity=ActivityInfo{2472a473 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1943): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1943): topRunningActivity=ActivityInfo{16dd3f30 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6355): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6355): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6355): Loading: webviewchromium
I/LibraryLoader( 6355): Time to load native libraries: 3 ms (timestamps 4024-4027)
I/LibraryLoader( 6355): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6355): Binding Chromium to main looper Looper (main, tid 1) {220ea112}
I/LibraryLoader( 6355): Expected native library version number "",actual native library version number ""
,I/chromium( 6355): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6355): Initializing chromium process, renderers=0
W/art     ( 6355): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6355): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  315): registerClient() client 0xb558a2a0, uid 10311
D/BluetoothManagerService( 1044): Message: 20
D/BluetoothManagerService( 1044): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cd1affc:true
W/chromium( 6355): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6355): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6355): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6355): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6355): Build Date: 12/12/14 금
I/Adreno-EGL( 6355): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6355): Remote Branch: 
I/Adreno-EGL( 6355): Local Patches: 
I/Adreno-EGL( 6355): Reconstruct Branch: 
W/chromium( 6355): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6355): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6355): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6355): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6355): CordovaWebView is running on device made by: LGE
W/art     ( 6355): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6355): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6355): Render dirty regions requested: true
I/OpenGLRenderer( 6355): Initialized EGL, version 1.4
D/OpenGLRenderer( 6355): Enabling debug mode 0
D/Atlas   ( 6355): Validating map...
D/SplitWindow( 1044): check instance of lgWin Window{3e64cb56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6355): LgDataFeature() Constructor: none
D/LgDataFeature( 6355): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1044): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1447): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1447): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1447):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1447): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1044): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1044): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1044): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1044): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26b007fe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1044): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1044): Displayed com.test.thalitest/.MainActivity: +617ms (total +685ms)
I/Timeline( 1044): Timeline: Activity_windows_visible id: ActivityRecord{30a0f693 u0 com.test.thalitest/.MainActivity t4} time:164508
I/Timeline( 6355): Timeline: Activity_idle id: android.os.BinderProxy@22bd72c2 time:164509
I/chromium( 6355): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6355): 
D/JsMessageQueue( 6355): Set native->JS mode to OnlineEventsBridgeMode
E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6355): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435078400
I/chromium( 6355): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6355): 
I/chromium( 6355): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6355): Initializing JXcore engine
W/jxcore-log( 6355): JXcore engine is ready
,I/art     ( 6355): Background sticky concurrent mark sweep GC freed 133860(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.648ms total 117.894ms
,W/Thread-724( 6425): type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[10268]" dev="sockfs" ino=10268 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-724( 6425): type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-724( 6425): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10004]" dev="sockfs" ino=10004 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-724( 6425): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-724( 6425): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[30216]" dev="sockfs" ino=30216 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6355): Starting JXcore engine
,W/jxcore-log( 6355): Platform android
W/jxcore-log( 6355): 
W/jxcore-log( 6355): Process ARCH arm
W/jxcore-log( 6355): 
,I/jxcore-log( 6355): JXcore Cordova bridge is ready!
I/jxcore-log( 6355): 
,W/jxcore-log( 6355): JXcore engine is started
,I/jxcore-log( 6355): Toggling radios to true
I/jxcore-log( 6355): 
,D/BluetoothAdapter( 6355): enable(): BT is already enabled..!
D/WifiService( 1044): New client listening to asynchronous messages
D/WifiServiceImplEx( 1044): setWifiEnabled: true pid=6355, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1044): setWifiEnabled: true pid=6355, uid=10311
E/WifiService( 1044): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1044): disconnect pid=6355, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1044):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1044): setLastSelectedConfiguration -1
E/WifiNative: ( 1044): [167,700,614 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1044): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1044): reconnect pid=6355, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6355): Radios toggled
I/jxcore-log( 6355): 
I/jxcore-log( 6355): My device name is: LGE-LG-D855
I/jxcore-log( 6355): 
,I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1,
,D/WifiNative-wlan0( 1044): DISCONNECT: returned true
D/Tethering( 1044): InitialState.processMessage what=4
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/Tethering( 1044): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1044): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1044): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine( 1044):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1044): [167,760,638 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1044): doBoolean: RECONNECT
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1044): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1044): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1044): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiNative-wlan0( 1044): RECONNECT: returned true
E/WifiStateMachine( 1044):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=167776
E/WifiStateMachine( 1044):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1044):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=167781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1044): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1044): hidePasspointNotification off =false
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=167792  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=167792  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=167800  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6444): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6444): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6444): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6444): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6444): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6444): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6444): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1044): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 5442:com.google.android.talk/u0a72 (adj 15): empty #17
,I/art     (  336): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 16.298ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 14.672ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 273us total 13.170ms
,W/libprocessgroup( 1044): failed to open /acct/uid_10072/pid_5442/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6444): LgDataFeature() Constructor: none
D/LgDataFeature( 6444): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
I/ActivityManager( 1044): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6498 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1044): Killing 5993:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10004/pid_5993/cgroup.procs: No such file or directory
,W/ResourcesManager( 6498): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6498): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6498): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6498): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6498): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6498): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6498): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6498): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6498): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6474): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/QRemote ( 6498): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PCSuite ( 6474): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6474): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6498): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6498): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6498): LgDataFeature() Constructor: none
D/LgDataFeature( 6498): LgDataFeature() Constructor Done, null
,V/SoundPool( 6498): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6498): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6498): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6498): doLoad: loading sample sampleID=1
V/SoundPool( 6498): Start decode
V/MediaPlayer[Native]( 6498): decode(31, 10857164, 17813)
I/QRemote ( 6498): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
,W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1432500, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6109): QS Service created
D/QRemote ( 6498): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
I/UEI.SmartControl( 6109): Service initServices...
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ba0 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e70 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434fb0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1526060 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb1432500, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb1432500, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
E/QRemote ( 6498): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
D/UEI.SmartCo,ntrol( 6109): QS start get config
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978224
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978384
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978544
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974965856
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434fb0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e70 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1003f10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb1432500, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac504000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac505000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac506000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac507000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac508000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac509000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50a000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50b000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50c000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50d000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50e000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac50f000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac510000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac511000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac512000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac513000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac514000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac515000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac516000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac517000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac518000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac519000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51a000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51b000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51c000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51d000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51e000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac51f000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac520000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac521000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac522000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac523000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac524000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac525000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac526000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac527000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac528000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac529000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac52a000, 0xb124a000, 4096)
,V/AudioCache(  315): write(0xb124a000, 4096)
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AudioCache(  315): memcpy(0xac52b000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac52c000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac52d000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac52e000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac52f000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac530000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac531000, 0xb124a000, 4096)
V/LGMDMManager( 6498): Create singleton instance
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac532000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac533000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac534000, 0xb124a000, 4096)
V/AudioCache(  315): write(0xb124a000, 4096)
V/AudioCache(  315): memcpy(0xac535000, 0xb124a000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb124a000, 280)
V/AudioCache(  315): memcpy(0xac536000, 0xb124a000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb1432500, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb1432500, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1432500, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434ba0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14349c0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1003f10 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434e70 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port, 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434fb0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 6498): close(31)
V/SoundPool( 6498): pointer = 0xa000d000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6498): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4330
I/UEI.SmartControl( 6109): Supports setup maps: true
,D/UEI.SmartControl( 6109): QS start statue = true Error code = 0
I/UEI.SmartControl( 6109): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6109): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6109): ### init IR Blaster...
D/serial_port( 6109): Configuring serial port
E/UEI.SmartControl( 6109): UEIBLaster setting for 616
I/UEI.SmartControl( 6109): Setting serial record hearder size = 2
I/UEI.SmartControl( 6109): configuring settings for MAXQ616
I/UEI.SmartControl( 6109): Get version...
D/UEI.SmartControl( 6109): serial port data available: 21
,D/UEI.SmartControl( 6109): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6109): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6109): QS saving settings...
D/UEI.SmartControl( 6109): IR Blaster version: 25672567
,D/UEI.SmartControl( 6109): serial port data available: 4
,I/UEI.SmartControl( 6109): Device manager: loading config....
,D/UEI.SmartControl( 6109): ----------- loading internal config...
W/ContextImpl( 6109): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6109): Loading SETTINGS...
,D/UEI.SmartControl( 6109): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6109): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6109): -----service ready thread exits
I/art     ( 1044): Explicit concurrent mark sweep GC freed 28000(1390KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.555ms total 133.268ms
E/UEI.SmartControl( 6109): Services init done
D/UEI.SmartControl( 6109): QS Service init finished
D/UEI.SmartControl( 6109): QS Service version name: 2.1.91
D/UEI.SmartControl( 6109): QS Service version code: 201091
D/UEI.SmartControl( 6109): Service requested: Control
,I/QRemote ( 6498): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6109): ------ IControl API: 11
D/UEI.SmartControl( 6109): File observer start...
E/UEI.SmartControl( 6109): IR Port is disabled: false
D/UEI.SmartControl( 6109): Starting file observer...
I/UEI.SmartControl( 6109): Registering callback...
I/UEI.SmartControl( 6109): ------ IControl API: 19
I/UEI.SmartControl( 6109): Registering Services Ready callback...
I/UEI.SmartControl( 6109): Notify client services are ready...
,I/QRemote ( 6498): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6498): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6498): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6498): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6498): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
D/UEI.SmartControl( 6109): Internal service binding...
I/UEI.SmartControl( 6109): ------ IControl API: 8
D/QRemote ( 6498): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6498): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6498): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6498): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6498): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6498): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6498): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6498): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6498): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453367966929]
D/QRemote ( 6498): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1044): Killing 6087:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/QRemote ( 6498): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1044): failed to open /acct/uid_10008/pid_6087/cgroup.procs: No such file or directory
,V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6498): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2669): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1044): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1044): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine( 1044):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
W/WifiMonitor( 1044): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine( 1044):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1044):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
E/WifiStateMachine( 1044):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
D/WifiNative-wlan0( 1044): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=169836  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=169863  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateASSOCIATING
,V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2669): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering( 1044): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1044): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=170042  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=170044  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1044):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1044): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1044):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6444): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6444): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6444): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1044):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6444): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : activeList=[]
E/WifiStateMachine( 1044):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=170055
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6444): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6444): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1044):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=170057
D/UsbSettingsControl( 6444): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1044):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=170058
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=170060
E/WifiStateMachine( 1044):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=170061
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=170062  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=170070  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateASSOCIATED
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2669): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1044): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1044): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1044): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=170084  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=170085  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1044):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=170085
E/WifiStateMachine( 1044):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=170086
D/WifiNative-wlan0( 1044): doString: [STATUS]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1044):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
I/WifiServiceExtension( 1044): setVHTCapabilityType  : false
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1044): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1044): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1044): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1044): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1044): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1044): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1044): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1044): NetworkAgent connected
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/WifiNative-wlan0( 1044): SAVE_CONFIG: returned true
E/WifiConfigStore( 1044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1044): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1044): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1044): doBoolean: SAVE_CONFIG
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1044): SAVE_CONFIG: returned true
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  311): Setting iface cfg
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1044): Start Dhcp Watchdog 1
E/WifiStateMachine( 1044):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=170134  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1044): StoppedState
D/DhcpStateMachine( 1044): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=170134  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1044): WaitBeforeStartState
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=170135  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1044):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=170136  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=170137  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=170137  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1044):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1044): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1044): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1044): doBoolean: SET ps 0
D/WifiNative-wlan0( 1044): SET ps 0: returned true
D/WifiNative-wlan0( 1044): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1044): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1044): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1044): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1044): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1044): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateCOMPLETED
D/LGWifiP2pService( 1044): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f35b8bc target=com.android.internal.util.StateMachine$SmHandler }
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService( 1044): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f35b8bc target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1044): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateCOMPLETED
D/DhcpStateMachine( 1044): DHCP Start wake lock is acquired.
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
,D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1044): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1044): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1044): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6559): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6559): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6559): version 5.5.6 starting
,E/dhcpcd  ( 6559): get_duid: m
D/dhcpcd  ( 6559): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 6559): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6559): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6559): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6559): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6559): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6559): wlan0: sending REQUEST (xid 0x94ff4b0b), next in 3.82 seconds
I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6355): 
,E/WifiStateMachine( 1044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/dhcpcd  ( 6559): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6559): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6559): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6559): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6559): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6559): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6559): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6559): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6559): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1044): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1044): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1044): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1044): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1044): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1044): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1044): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1044): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1044): RunningState
E/WifiStateMachine( 1044):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1044):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1044): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1044): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1044): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1044): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1044): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1044): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1044): doBoolean: SET ps 1
D/WifiNative-wlan0( 1044): SET ps 1: returned true
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1044):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1044): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1044): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1044): Adding iface wlan0 to network 100
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/ConnectivityService( 1044): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1044): Adding Route [fe80::/64 -> :: wlan0] to network 100
E/WifiStateMachine( 1044): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1044): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/WifiHS20( 1044): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1044): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1044): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1044): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
V/WfdStateTracker( 1943): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1044): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1044): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1044): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1044): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Connected
D/ConnectivityService( 1044): currentScore = 0, newScore = 20
D/ConnectivityService( 1044):    accepting network in place of null
D/ConnectivityService( 1044): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1044): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1044):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1044): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1044): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
D/CSLegacyTypeTracker( 1044): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1044): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1044): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1044): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1044): validation of new default Network = false
D/ConnectivityService( 1044): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1044): enableDataServiceNotify 
D/DSQN    ( 1044): start dsqn bin
,D/LocSvc_java( 1044): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1044): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1044): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1044): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1044): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1044): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
W/dsqn    ( 6603): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6603): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 6603): DSQN ssw
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org succeed
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6474): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6474): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6498): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6498): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6498): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6474): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6474): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6444): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6444): MCCMNC not supported: null
,D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6498): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6498): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6498): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,V/NetworkPolicy( 1044): [LG_RESTRICTED] checkMobilePolicy_type()
D/LocSvc_java( 1044): NTP server : europe.pool.ntp.org
D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1044): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1044): start to monitor internet connection
,D/LocSvc_java( 1044): NTP server returned: 1453367970792 (Thu Jan 21 10:19:30 GMT+01:00 2016) reference: 172244 certainty: 44 system time offset: 1121
D/LocSvc_java( 1044): Sending msg: 10 arg1:0 arg2:1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 09:19:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453367969694], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453367969670]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Validated
D/ConnectivityService( 1044): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1044): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1044): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WIFI    ( 1044): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1044):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/rmt_storage(  307): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  307): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  307): wakelock acquired: 1, error no: 42
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  307): 
,I/rmt_storage(  307): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  906): [IMS_FATAL]| 3347 | 913 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6355): 
,I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6355): 
I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6355): 
,I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6355): 
,I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6355): 
,I/jxcore-log( 6355): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6355): 
D/UEI.SmartControl( 6109): Internal timer expired: 3
,D/UEI.SmartControl( 6109): unbind internal service
,D/serial_port( 6109): close(fd = 24)
,I/UEI.SmartControl( 6109): Serial port is closed.
V/WifiInternetCheck( 1044): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1044): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1044): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/AlarmManagerService( 1044): Setting time of day to sec=1453367973
,W/AlarmManagerService( 1044): Unable to set rtc to 1453367973: Invalid argument
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6056): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{24b7af66 type 0 when 1453367970658 com.android.vending} when 1453367970658
,D/LIA_Informant_Tips_DateChangeManager( 2671): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2671): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-21 10:19:33...... Request
I/LIA_Informant_Tips_LogTracer( 2671): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 151, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2671): DateInfo : SmartTips Total Working Day Count = 151
D/LIA_Informant_Tips_DateChangeManager( 2671): DateInfo : UserGuide Working Duration Count = 8
I/[SystemUI]Clock( 1447): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2671): DateInfo : Last Date Check Time = 2016-01-21 10:19:33
I/SecureClockService( 1943): Intent.ACTION_TIME_CHANGED 
I/LgeClockWidgetControlView( 1447): time changed, timezoneChanged : false
I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1044): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2071): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=21 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2071): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 21
I/[LGHome]LGCalendarIcon( 2071): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 21
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,I/NetworkStateForAutoUpdateMonitor( 5622): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5622): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 5622): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 5622): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 5622): onReceive
,D/AppUp4:CustFacade( 5622): Context : android.app.ReceiverRestrictedContext@3c1ab89d
D/AppUp4:CustFacade( 5622): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5622): isPhone : true
D/AppUp4:CustModeStarterReceiver( 5622): begin check event
I/AppUp4:CustModeStarterReceiver( 5622): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5622): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 5622): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5622): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5622): handleAsyncCustNotification do not startCustService
V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,I/ActivityManager( 1044): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6640 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 2745): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4105): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 2745): DownloadService onCreate
,I/DownloadManager( 2745): in removeSpuriousFiles
,V/DownloadManager( 2745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4105): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4105): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4105): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/eas_req ( 6144): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@aec921f on behalf of 2745
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 2745): in trimDatabase
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@1e39d96c on behalf of 2745
V/DownloadManager( 2745): DownloadService onStartCommand
V/DownloadManager( 2745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@2b52313b on behalf of 2745
V/DownloadManager( 2745): processing inserted download 1
V/DownloadManager( 2745): processing inserted download 4
,V/DownloadManager( 2745): processing inserted download 7
V/DownloadManager( 2745): processing inserted download 8
V/DownloadManager( 2745): processing inserted download 9
,V/DownloadManager( 2745): processing inserted download 10
V/DownloadManager( 2745): processing inserted download 16
V/DownloadManager( 2745): processing inserted download 17
V/DownloadManager( 2745): processing inserted download 18
V/DownloadManager( 2745): processing inserted download 21
V/DownloadManager( 2745): processing inserted download 22
I/ActivityManager( 1044): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6663 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 2745): DownloadService onDestroy
,I/HubEmail( 6144): JNI_OnLoad()
I/HubEmail( 6144): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6144): registerNatives()
I/HubEmail( 6144): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6144): registerNativeMethods()
I/HubEmail( 6144): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6144): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1044): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6682 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6640): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/Settings( 6144): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6144): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = true
D/PhoneState( 3310): setPdpRejectCasuse : false
,W/DriveInitializer( 2333): Background init thread started
,W/GAV2    ( 6640): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3114): Thermal-Lib-Client: Client request sent
I/BooksApp( 6640): Created application version: 3.2.35 (30235)
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider( 1044): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/GpsLocationProvider( 1044): No APN found to select.
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5748): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5748): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5748): [1] 5.onFinished: Scheduling replication attempt 4.
,W/DriveInitializer( 2333): Background init thread ended
I/BooksSync( 6640): Starting books sync
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
,D/DelayedSyncController( 6682): Delaying sync.
,V/FormManager( 6663): There are no updated forms. The schedule will be deleted.
,I/ActivityManager( 1044): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6735 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/FormManager( 6663): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1044): Killing 5643:com.android.contacts/u0a19 (adj 15): empty #17
D/BooksSync( 6640): started syncMyEbooks
,W/libprocessgroup( 1044): failed to open /acct/uid_10019/pid_5643/cgroup.procs: No such file or directory
,I/ActivityManager( 1044): Killing 5690:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/art     ( 2124): Explicit concurrent mark sweep GC freed 11799(630KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 736us total 23.978ms
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmBroadcastReceiver( 6735): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6735): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6735): Service onCreate
D/DrmService( 6735): Received new request = 2
,I/DrmSntpClient( 6735): Start Sync process
D/DrmSntpClient( 6735): Server : 0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1044): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6760 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1044): failed to open /acct/uid_10080/pid_5690/cgroup.procs: No such file or directory
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  311): res_queryN name = pool.ntp.org succeed
,W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
I/art     ( 6760): Almond Protected OAT
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/LGDrmClient( 6735): _DRM_ServiceGet() : Bind lgdrm service
,D/WeatherApplication( 6760): removeAccount
V/ILGDrmService(  321): eDRM_SetDRMTime +++
I/LGDRM   (  321): [DRM] SET TIME : YR=2016, MON=1, DAY=21
I/LGDRM   (  321): [DRM] SET TIME : HR=9, MIN=19, SEC=33
D/WeatherApplication( 6760): Account.length = 0
E/WeatherApplication( 6760): OPERATOR:OPEN
D/WeatherAncestor( 6760): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:19:34
D/Weather.Utils( 6760): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6760): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6760): 2 : This is isUpdating : false
D/WeatherAncestor( 6760): connectivity changed - connection : true
,D/WeatherService( 6760): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6760): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6760): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6760): 2 : Cache is not up-to-date, count: 0
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
V/ILGDrmService(  321): eDRM_SetDRMTime ---
I/DrmSntpClient( 6735): Synched
,D/DrmService( 6735): Completed !! request = 2
D/DrmService( 6735): Request count = 0
V/DrmService( 6735): Service onDestroy
I/ActivityManager( 1044): Killing 6179:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/Weather_cast( 6760): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6760): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:19:34
I/ActivityManager( 1044): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6780 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1044): Killing 5718:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
W/libprocessgroup( 1044): failed to open /acct/uid_10061/pid_6179/cgroup.procs: No such file or directory
W/libprocessgroup( 1044): failed to open /acct/uid_10097/pid_5718/cgroup.procs: No such file or directory
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7933781160835184171&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6780): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6780): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6780): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6780): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1044): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6808 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6808): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1044): Explicit concurrent mark sweep GC freed 61755(2MB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.227ms total 77.361ms
,V/WifiInternetCheck( 1044): isHttpConnectionAvailable - We got a valid response : 204
,I/WebViewFactory( 6780): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6780): Loading: webviewchromium
I/LibraryLoader( 6780): Time to load native libraries: 2 ms (timestamps 6615-6617)
I/LibraryLoader( 6780): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6780): Binding Chromium to main looper Looper (main, tid 1) {3c26df4b}
I/LibraryLoader( 6780): Expected native library version number "",actual native library version number ""
I/chromium( 6780): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6780): Initializing chromium process, renderers=0
,W/art     ( 6780): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  315): registerClient() client 0xb1427d20, uid 10093
W/AudioManagerAndroid( 6780): Requires BLUETOOTH permission
W/chromium( 6780): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6780): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6780): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 6780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6780): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6780): Build Date: 12/12/14 금
I/Adreno-EGL( 6780): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6780): Remote Branch: 
I/Adreno-EGL( 6780): Local Patches: 
I/Adreno-EGL( 6780): Reconstruct Branch: 
I/GLSActivity( 2124): [ac] getting account id
,I/GLSUser ( 2124): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/NSApplication( 6780): Starting up...
,I/ActivityManager( 1044): Killing 6223:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6223/cgroup.procs: No such file or directory
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2333): SYNC; picasa accounts
D/NetworkLogImpl( 2333): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2333): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 2333): num queued entries: 0
I/iu.UploadsManager( 2333): num updated entries: 0
I/iu.SyncManager( 2333): NEXT; no task
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PostponalbeReceiver( 6056): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1044): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6880 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
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
D/ContactsSyncAdapter( 2124): innerSync failed
D/ContactsSyncAdapter( 2124): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2124): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2124): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2124): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2124): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 87204, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
W/Kids    ( 2333): [AccountUtils] Account not ready
W/Kids    ( 2333): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2333): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2333): 	at java.lang.Thread.run(Thread.java:818)
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
D/ALBootInit( 6880): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6880): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6880): [setNextAlert] start
D/Alarms  ( 6880): [setNextAlert] (1)
,D/Alarms  ( 6880):  minTime  = 0
D/Alarms  ( 6880):  -- OK multi -- 0
E/jeny.kim( 6880): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6880): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/CommonUtil( 6880): BUILD Country: EU
,D/Alarms  ( 6880): broadcastToWidgetProvider : false
D/Alarms  ( 6880): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1044): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6880): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6880): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f6f4199
V/DigitalAppWidgetProvider( 6880): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f6f4199
,D/QuickCoverProvider( 6880): onReceiver
I/indal   ( 1402): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1402): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6760): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:19:35
D/Weather.Utils( 6760): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6760): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6760): 2 : This is isUpdating : false
D/WeatherService( 6760): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1db1bc5e
D/ForecastDataCache( 6760): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6760): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6760): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6760): 2 : set auto-update time : 1/21 13:19
,D/WeatherAncestor( 6760): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:19:35
I/ActivityManager( 1044): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6902 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1044): Killing 6258:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6258/cgroup.procs: No such file or directory
D/TimeService( 6902): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453367976050
D/        ( 6902): TimeServiceNative: User Time to be set is 1453367976050
D/QC-time-services( 6902): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6902): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6902): Lib:time_genoff_operation: pargs->ts_val = 1453367976050
D/QC-time-services( 6902): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  357): Daemon: Connection accepted:time_genoff
D/QC-time-services(  357): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453367976050
D/QC-time-services(  357): Daemon:genoff_opr: Base = 2, val = 1453367976050, operation = 0
D/QC-time-services(  357): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/31/70 2:31:51
D/QC-time-services(  357): Daemon:Value read from RTC seconds = 12969111000
D/QC-time-services(  357): Daemon:new time 1453367976050 
D/QC-time-services(  357): Daemon: delta 1440398865050 genoff 1440398865050 
D/QC-time-services(  357): Daemon:genoff_persistent_update: Writing genoff = 1440398865050 to memory
D/QC-time-services(  357): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  357): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  357): Updating the TOD offset
D/QC-time-services(  357): Daemon:genoff_persistent_update: Writing genoff = 1440398865050 to memory
D/QC-time-services(  357): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  357): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  357): Daemon:Update to modem bit set
D/QC-time-services(  357): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  357): Daemon: Base = 2, Value being sent to MODEM = 1124434065050
E/QC-time-services( 6902): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  357): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  357): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1044): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6925 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1044): Killing 6241:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  336): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 12.066ms
D/GCM     ( 2124): Connected
I/art     (  336): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.783ms
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 180us total 9.329ms
W/libprocessgroup( 1044): failed to open /acct/uid_10005/pid_6241/cgroup.procs: No such file or directory
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 2124): Message class com.google.f.a.a.p
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/CalendarApplication( 6925): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6925): [debug_displayParseInfos] preference keys.size() = 44
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PreferenceKeysParser( 6925): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@19ef9b74, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3c1ab89d, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@220ea112, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1b3a40e3, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2a24fae0, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1f6f4199, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1db1bc5e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1ac6083f, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8ee50c, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@25e95e55, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@9d9406a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1f1ce95b, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@25cb45f8, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1cae8ad1, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1342f936, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1136c037, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@246ac9a4, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@23c0030d, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@22bd72c2, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@7ad28d3, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2d5cdc10, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1ff6c309, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2d73f90e, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1f177f2f, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@331ba93c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@10bf86c5, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3dfa981a, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3c26df4b, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@33981d28, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@596ca41, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@21a1be6, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@13822527, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@18e5e3d4, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2f44c97d, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@295c1072, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1361ecc3, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@38a76940, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@8d98079, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2056c1be, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@aec921f, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1e39d96c, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1468
D/GeneralPreferenceUtils( 6925): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6925): [init]
I/Config  ( 6925): LGCalendar ver.4.40.16
I/Config  ( 6925): start check model
I/Config  ( 6925): start check native_ca
I/Config  ( 6925): Config Operator=OPEN, Country=EU
D/Config  ( 6925): [setDefaultValuesToPref]
D/Config  ( 6925): [parseProfiles]
D/ProfilesParser( 6925): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6925): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6925): [updateProfiletoCountryInfo]
D/GeneralPreference( 6925): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6925): [updateWidgets] 
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7933781160835184171&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
I/InitNotificationRingtoneService( 6925): Start InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6925): [onReceive]
D/CalendarWidgetProvider( 6925): [onReceive]
W/HolidayIntentService( 6925): onHandleIntent
D/CalendarWidgetProvider( 6925): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 6925): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/CalendarTypeController( 6925): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 6925): readJsonAsset : holiday.json
D/WeekWidgetProvider( 6925): [onReceive]
D/CalendarWidgetProvider( 6925): [onReceive]
D/CalendarWidgetProvider( 6925): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6925): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6925): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/HolidayIntentService( 6925): onHandleIntent:holiday data empty
V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4330
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/DigitalAppWidgetProvider( 6880): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6760): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:19:36
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/Weather.Utils( 6760): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6760): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6760): 2 : This is isUpdating : false
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6925): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6925): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6925): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6925): End InitializeAlertRingtoneService.onHandleIntent
I/art     ( 1044): Explicit concurrent mark sweep GC freed 19232(899KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.568ms total 86.547ms
D/Weather_cast( 6760): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6760): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:19:36
I/ActivityManager( 1044): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6954 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6474:com.lge.sync/1000 (adj 15): empty #17
I/Sensors (  500): sns_time.c(596):Rollover predicted. Old rollover count: 0, dsps ts: 5970168
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 177858747226; DSPS: 5970171; Offset : -4351875029
W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6474/cgroup.procs: No such file or directory
W/ResourcesManager( 6954): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 6954): LgDataFeature() Constructor: none
D/LgDataFeature( 6954): LgDataFeature() Constructor Done, null
,I/jxcore-log( 6355): Test app app.js loaded
I/jxcore-log( 6355): 
I/chromium( 6355): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6355): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6355): BLE advertisement is supported
I/jxcore-log( 6355): 
I/Babel   ( 6954): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6954): MmsConfig.loadMmsSettings
,I/Babel   ( 6954): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6954): MmsConfig.loadFromDatabase
E/Babel   ( 6954): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6954): MmsConfig.loadFromResources
E/Babel   ( 6954): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6954): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6954): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6954): Unsupported mime audio/evrc
W/AudioCapabilities( 6954): Unsupported mime audio/qcelp
W/VideoCapabilities( 6954): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6954): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6954): Unsupported mime audio/qcelp
W/AudioCapabilities( 6954): Unsupported mime audio/evrc
,W/VideoCapabilities( 6954): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6954): Unsupported mime video/divx
W/VideoCapabilities( 6954): Unsupported mime video/divx311
W/VideoCapabilities( 6954): Unsupported mime video/divx4
,W/VideoCapabilities( 6954): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6954): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6954): Unsupported mime audio/eac3
W/AudioCapabilities( 6954): Unsupported mime audio/ac3
W/AudioCapabilities( 6954): Unsupported mime audio/g726
W/ResourcesManager( 6954): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/AudioCapabilities( 6954): Unsupported mime audio/wma-voice
W/ResourcesManager( 6954): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6954): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6954): Unsupported mime audio/adpcm
W/VideoCapabilities( 6954): Unsupported mime video/theora
,W/VideoCapabilities( 6954): Unsupported mime video/mjpg
V/JNIHelp ( 6954): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6954): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6954): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6954): UserRecoverableAuthException.
,E/Babel   ( 6954): cfq: BadAuthentication
E/Babel   ( 6954): 	at cfn.a(Unknown Source)
E/Babel   ( 6954): 	at f.a(PG:191)
E/Babel   ( 6954): 	at ava.a(PG:88)
E/Babel   ( 6954): 	at ava.a(PG:128)
E/Babel   ( 6954): 	at bjs.a(PG:255)
E/Babel   ( 6954): 	at bep.a(PG:602)
E/Babel   ( 6954): 	at bep.a(PG:469)
E/Babel   ( 6954): 	at bpo.run(PG:1141)
E/Babel   ( 6954): Error getting auth token
E/Babel   ( 6954): bxl
E/Babel   ( 6954): 	at f.a(PG:201)
E/Babel   ( 6954): 	at ava.a(PG:88)
E/Babel   ( 6954): 	at ava.a(PG:128)
E/Babel   ( 6954): 	at bjs.a(PG:255)
E/Babel   ( 6954): 	at bep.a(PG:602)
E/Babel   ( 6954): 	at bep.a(PG:469)
E/Babel   ( 6954): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6954): error sending REQ[fc:4; creat:1453367857657; type:bev-824751934]; took 113 ms (error code == 100)
E/Babel   ( 6954): Account registration failedRedacted-21
E/Babel   ( 6954): bph: null -- null
E/Babel   ( 6954): 	at ava.a(PG:120)
E/Babel   ( 6954): 	at ava.a(PG:128)
E/Babel   ( 6954): 	at bjs.a(PG:255)
E/Babel   ( 6954): 	at bep.a(PG:602)
E/Babel   ( 6954): 	at bep.a(PG:469)
E/Babel   ( 6954): 	at bpo.run(PG:1141)
I/Babel   ( 6954): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6954): Account sign in complete with state 106account: Redacted-21
I/art     ( 6954): Note: end time exceeds epoch: 
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2124): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/Babel   ( 6954): Unexpected exception while authenticating.
E/Babel   ( 6954): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6954): 	at cfn.b(Unknown Source)
E/Babel   ( 6954): 	at cfn.a(Unknown Source)
E/Babel   ( 6954): 	at f.a(PG:188)
E/Babel   ( 6954): 	at ava.b(PG:143)
E/Babel   ( 6954): 	at bnr.run(PG:5415)
E/Babel   ( 6954): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6954): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6954): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
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
,E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7933781160835184171&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{1d03e5fb type 2 when 179644 com.google.android.gms} when 179644
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksSync( 6640): Soft error: 
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7933781160835184171&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
,E/BooksSync( 6640): Sync error
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7933781160835184171&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
I/BooksSync( 6640): Finished books sync
I/ActivityManager( 1044): Killing 6444:com.android.settings/1000 (adj 15): empty #17
,D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 27104, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6444/cgroup.procs: No such file or directory
,I/VacuumService( 2124): Vacuum at: now=1453367978797 tag=VacuumService
,I/GoogleURLConnFactory( 2124): Using platform SSLCertificateSocketFactory
,W/Uploader( 2124): No account for auth token provided
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
,I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3114): Thermal-Lib-Client: Client request sent
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2124): No account for auth token provided
I/GAV2    ( 6640): Thread[GAThread,5,main]: No campaign data found.
,W/Uploader( 2124): No account for auth token provided
,W/Uploader( 2124):  no longer exists, so no auth token.
,W/Uploader( 2124): No account for auth token provided
I/GAV4    ( 6780): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1044): Killing 5748:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10044/pid_5748/cgroup.procs: No such file or directory
,I/ActivityManager( 1044): Killing 5622:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_10011/pid_5622/cgroup.procs: No such file or directory
,I/InputReader( 1044): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
D/SplitUIService( 1873): replaced split : contains_com.google.android.talk / true
,D/SplitUIManager( 1873): split_name #11 / not available #0
I/SplitUIService( 1873): split app #11
,I/ActivityManager( 1044): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7045 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 2071): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/administrator( 1044): Handling package changes for user 0
,W/ResourcesManager( 2071): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2071): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7045): onCreate
,W/AppUp4:DB( 7045):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7045):  setFingerPrint start
I/AppUp4:DB( 7045):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7045):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7045):  SDK version = 21
I/AppUp4:DB( 7045):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7045): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7045): onReceive
I/NotificationService( 1044): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1044): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1044): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7045): LgDataFeature() Constructor: none
W/ResourcesManager( 1044): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LgDataFeature( 7045): LgDataFeature() Constructor Done, null
W/ResourceType( 1044): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AppUp4:CustFacade( 7045): Context : android.app.ReceiverRestrictedContext@3c1ab89d
D/AppUp4:CustFacade( 7045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7045): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7045): begin check event
I/AppUp4:CustModeStarterReceiver( 7045): Event For Nothing, skip.
I/[LGHome]EVENT( 2071): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager( 1044): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7081 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6663:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10026/pid_6663/cgroup.procs: No such file or directory
W/ResourcesManager( 7081): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7081): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7081): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7081): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7081): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7081): BUILD Country: EU
I/SystemConfig( 7081): BUILD Operator: OPEN
,I/ActivityManager( 1044): Killing 5670:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10027/pid_5670/cgroup.procs: No such file or directory
,I/SystemConfig( 7081): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7081): existFile = false
,I/SystemConfig( 7081): canReadFile = false
I/SystemConfig( 7081): systemFeature RCS result false
D/SystemConfig( 7081): refreshRcsSupport() :false
I/ActivityManager( 1044): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7104 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7104): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7104): Total System Memory = 2995761152
,D/SystemHelper( 7104): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1044): Killing 6682:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10057/pid_6682/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4370): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager( 1044): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7124 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4370): UpdateCorporaTask done [took 101 ms] updated apps [took 101 ms] 
,I/LockScreenSettings( 7124): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7124): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7124): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7124): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7124): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7124): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7124): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1044): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7142 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6735:com.lge.drmservice/u0a62 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_10062/pid_6735/cgroup.procs: No such file or directory
,D/Finsky  ( 7142): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7142): LgDataFeature() Constructor: none
,D/LgDataFeature( 7142): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7142): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1044): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7181 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7142): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7142): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 2745): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@2785c5b1 on behalf of 7142
W/ResourcesManager( 7181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7142): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7142): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7142): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/MultiDex( 7181): VM with version 2.1.0 has multidex support
I/MultiDex( 7181): install
I/MultiDex( 7181): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7142): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1044): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7218 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{1cf89949 type 0 when 1453367994351 com.android.vending} when 1453367994351
,I/PeopleContactsSync( 2333): CP2 sync disabled
,V/JNIHelp ( 7181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 7218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,I/MultiDex( 7218): VM with version 2.1.0 has multidex support
I/MultiDex( 7218): install
I/MultiDex( 7218): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7218): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@399bcba5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7181): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2124): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2124): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/ActivityThread( 7218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7218): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@399bcba5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7218): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2124): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2124): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/NativeLibraryUtils( 7218): Install did not work
W/NativeLibraryUtils( 7218): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7218): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7218): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7218): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7218): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7218): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7218): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7218): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7218): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7218): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7218): 	... 4 more
D/LocationInitializer( 2333): Restart initialization of location
D/WearableService( 7218): callingUid 10005, callindPid: 7218
V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 2333): Restart initialization of location
,E/MDM     ( 1820): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1820): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/art     ( 2124): Explicit concurrent mark sweep GC freed 36555(2MB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 5.666ms total 64.685ms
,V/Finsky  ( 7142): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1044): Explicit concurrent mark sweep GC freed 33240(1561KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 3.025ms total 197.461ms
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{17887029 type 0 when 1453367995075 com.android.vending} when 1453367995075
,D/Finsky  ( 7142): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 5.
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7142): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7142): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7142): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
I/ActivityManager( 1044): Killing 6144:com.lge.email/u0a23 (adj 15): empty #17
,D/DeviceConnectionService( 1820): client connected with version: 7571000
I/ActivityManager( 1044): Killing 6780:com.google.android.apps.magazines/u0a93 (adj 15): empty #18
,W/libprocessgroup( 1044): failed to open /acct/uid_10023/pid_6144/cgroup.procs: No such file or directory
,W/libprocessgroup( 1044): failed to open /acct/uid_10093/pid_6780/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 197861464772; DSPS: 6625620; Offset : -4351873937
,I/ActivityManager( 1044): Killing 6056:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6056/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{850fd7d type 2 when 209550 android} when 209550
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2124): innerSync failed
D/ContactsSyncAdapter( 2124): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2124): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2124): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2124): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2124): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2124): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2124): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 209550, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1044): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 275010, reason: 10019
E/WifiStateMachine( 1044):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1044):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 217863096743; DSPS: 7281034; Offset : -4351890331
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{13916670 type 0 when 1453368015328 com.android.vending} when 1453368015328
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 237865217777; DSPS: 7936463; Offset : -4351874854
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{2940d3d2 type 2 when 239769 android} when 239769
,I/BooksSync( 6640): Starting books sync
,D/BooksSync( 6640): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
,D/LgeQuickCoverNotificationData( 1402): showAll3
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
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1740550313459373430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1740550313459373430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
,E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1740550313459373430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
E/BooksSync( 6640): Soft error: 
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1740550313459373430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
,E/BooksSync( 6640): Sync error
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1740550313459373430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
I/BooksSync( 6640): Finished books sync
D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{3259d62c type 2 when 241305 android} when 241305
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 257867066571; DSPS: 8591884; Offset : -4351887710
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{2189c8f5 type 2 when 269847 android} when 269847
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 277869190678; DSPS: 9247313; Offset : -4351869317
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 297871055046; DSPS: 9902734; Offset : -4351866495
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{2563668a type 2 when 309404 android} when 309404
,I/BooksSync( 6640): Starting books sync
,D/BooksSync( 6640): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1044): Explicit concurrent mark sweep GC freed 31326(1393KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.102ms total 113.853ms
,V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5586253648713325469&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5586253648713325469&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2124): Explicit concurrent mark sweep GC freed 33151(1957KB) AllocSpace objects, 14(2016KB) LOS objects, 51% free, 30MB/62MB, paused 2.062ms total 72.331ms
,V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5586253648713325469&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
E/BooksSync( 6640): Soft error: 
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5586253648713325469&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
,E/BooksSync( 6640): Sync error
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5586253648713325469&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
I/BooksSync( 6640): Finished books sync
D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309404, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 317873063007; DSPS: 10558160; Offset : -4351872564
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 337875079666; DSPS: 11213586; Offset : -4351870143
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{21e8ef24 type 2 when 339442 android} when 339442
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,I/ActivityManager( 1044): Killing 6902:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6902/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 357877054606; DSPS: 11869011; Offset : -4351878768
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 377879205692; DSPS: 12524442; Offset : -4351894561
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 397881687716; DSPS: 13179883; Offset : -4351884434
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 417883773333; DSPS: 13835311; Offset : -4351873987
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1044): battery changed pluggedType: 2
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3692): Disconnected process message: 10, size: 0
D/LEDHandler( 1943): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1943): Battery Level Remaining: 100%
D/LEDHandler( 1943): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 437885797336; DSPS: 14490737; Offset : -4351864117
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated(),
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{2e2fa8d type 0 when 1453368232715 com.google.android.gms} when 1453368232715
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,I/EventLogService( 2333): Aggregate from 1453366432616 (log), 1453366432616 (data)
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{15e4f28e type 2 when 444907 android} when 444907
,I/BooksSync( 6640): Starting books sync
,D/BooksSync( 6640): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
,D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8323684163294998264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8323684163294998264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8323684163294998264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
E/BooksSync( 6640): Soft error: 
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8323684163294998264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
,E/BooksSync( 6640): Sync error
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8323684163294998264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
I/BooksSync( 6640): Finished books sync
D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 444907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 457887591339; DSPS: 15146156; Offset : -4351870678
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{2b1b3d08 type 2 when 474921 android} when 474921
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 477889435654; DSPS: 15801577; Offset : -4351887960
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7142): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7142): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7142): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7142): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7142): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7142): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7142): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 7142): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 497891920855; DSPS: 16457018; Offset : -4351874605
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 517894013139; DSPS: 17112447; Offset : -4351888061
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 537902664746; DSPS: 17768090; Offset : -4351872955
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 557904565727; DSPS: 18423512; Offset : -4351864089
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 577906456189; DSPS: 19078934; Offset : -4351865690
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 597908510087; DSPS: 19734362; Offset : -4351886989
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1044): battery changed pluggedType: 2
D/LEDHandler( 1943): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1943): Battery Level Remaining: 100%
D/LEDHandler( 1943): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3692): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 617911014508; DSPS: 20389804; Offset : -4351885113
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 637913081947; DSPS: 21045231; Offset : -4351862248
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 657915120064; DSPS: 21700658; Offset : -4351868834
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 677916970421; DSPS: 22356079; Offset : -4351879971
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 697919090830; DSPS: 23011508; Offset : -4351865379
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{27f98aa type 2 when 711674 android} when 711674
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,I/BooksSync( 6640): Starting books sync
,D/BooksSync( 6640): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1402): onNotificationPosted
E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
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
,D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9089610675500213586&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1044): Explicit concurrent mark sweep GC freed 27868(1284KB) AllocSpace objects, 10(1184KB) LOS objects, 33% free, 44MB/66MB, paused 3.203ms total 164.040ms
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
W/ApiaryClient( 6640): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9089610675500213586&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6640): Authentication error
E/BooksAccountManager( 6640): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6640): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6640): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6640): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6640): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6640): Error response from books API: {
W/ApiaryClient( 6640):  "error": {
W/ApiaryClient( 6640):   "errors": [
W/ApiaryClient( 6640):    {
W/ApiaryClient( 6640):     "domain": "global",
W/ApiaryClient( 6640):     "reason": "required",
W/ApiaryClient( 6640):     "message": "Login Required",
W/ApiaryClient( 6640):     "locationType": "header",
W/ApiaryClient( 6640):     "location": "Authorization"
W/ApiaryClient( 6640):    }
W/ApiaryClient( 6640):   ],
W/ApiaryClient( 6640):   "code": 401,
W/ApiaryClient( 6640):   "message": "Login Required"
W/ApiaryClient( 6640):  }
W/ApiaryClient( 6640): }
,W/ApiaryClient( 6640): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9089610675500213586&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6640): Headers:
W/ApiaryClient( 6640): accept-encoding: [gzip]
W/ApiaryClient( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6640): gdata-version: 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 717921834156; DSPS: 23666958; Offset : -4351868531
,E/BooksSync( 6640): Soft error: 
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9089610675500213586&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
,E/BooksSync( 6640): Sync error
E/BooksSync( 6640): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6640): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9089610675500213586&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6640): Headers:
E/BooksSync( 6640): accept-encoding: [gzip]
E/BooksSync( 6640): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6640): gdata-version: 2
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6640): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6640): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6640): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6640): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6640): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6640): {
E/BooksSync( 6640):  "error": {
E/BooksSync( 6640):   "errors": [
E/BooksSync( 6640):    {
E/BooksSync( 6640):     "domain": "global",
E/BooksSync( 6640):     "reason": "required",
E/BooksSync( 6640):     "message": "Login Required",
E/BooksSync( 6640):     "locationType": "header",
E/BooksSync( 6640):     "location": "Authorization"
E/BooksSync( 6640):    }
E/BooksSync( 6640):   ],
E/BooksSync( 6640):   "code": 401,
E/BooksSync( 6640):   "message": "Login Required"
E/BooksSync( 6640):  }
E/BooksSync( 6640): }
E/BooksSync( 6640): 
E/BooksSync( 6640): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6640): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6640): 	... 8 more
I/BooksSync( 6640): Finished books sync
D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 711674, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 737923749097; DSPS: 24322381; Offset : -4351876197
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{3a05a044 type 2 when 741763 android} when 741763
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 757925558620; DSPS: 24977800; Offset : -4351867159
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 777927409394; DSPS: 25633221; Offset : -4351878113
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 797929258344; DSPS: 26288642; Offset : -4351890684
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,I/DigitalAppWidgetProvider( 6880): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 6880): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f6f4199
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 817931826983; DSPS: 26944086; Offset : -4351885522
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 837933678277; DSPS: 27599506; Offset : -4351865204
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 857935824571; DSPS: 28254937; Offset : -4351885658
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 877937955501; DSPS: 28910366; Offset : -4351860571
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 897939981743; DSPS: 29565793; Offset : -4351878929
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 917942792674; DSPS: 30221245; Offset : -4351875667
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 937944766103; DSPS: 30876670; Offset : -4351885828
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,W/bt-smp  ( 3692): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3692): Plain text(LSB ~ MSB) = 2b 5e 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3692): Encrypted text(LSB ~ MSB) = 3f b8 d9 70 fc cf 61 d3 b1 52 e4 e9 2a 0c 93 fd 
,W/bt-btm  ( 3692): Stopping oneshot timer
V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{23d2252d type 2 when 941748 com.android.bluetooth} when 941748
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 957946978908; DSPS: 31532102; Offset : -4351870290
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 977949064369; DSPS: 32187530; Offset : -4351860102
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 997951247123; DSPS: 32842962; Offset : -4351874614
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1017953223729; DSPS: 33498387; Offset : -4351881675
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1037955772471; DSPS: 34153830; Offset : -4351865685
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1057957351891; DSPS: 34809242; Offset : -4351873439
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1077959474123; DSPS: 35464672; Offset : -4351887411
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,D/Finsky  ( 7142): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{fe467f3 type 0 when 1453368631479 com.android.vending} when 1453368631479
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{34de7cb0 type 2 when 1077448 com.google.android.gms} when 1077448
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/GCM     ( 2124): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Procstats( 2333): User is not opted-in to Usage & Diagnostics.
,D/Diskstats( 2333): User is not opted-in to Usage & Diagnostics.
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7142): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 7142): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7142): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7142): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
D/DeviceConnectionService( 1820): client connected with version: 7571000
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1097962249792; DSPS: 36120123; Offset : -4351888661
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1117964326764; DSPS: 36775551; Offset : -4351887013
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{108f8635 type 0 when 1453368908703 com.android.vending} when 1453368908703
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1137966108058; DSPS: 37430969; Offset : -4351875686
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{3ef9e688 type 0 when 1453368938553 com.android.vending} when 1453368938553
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2124): Explicit concurrent mark sweep GC freed 36552(2MB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.430ms total 36.464ms
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1157968087322; DSPS: 38086394; Offset : -4351880065
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1044): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1044): handleNetworkStateChange: Could not parse disconnect string
D/Tethering( 1044): InitialState.processMessage what=4
,D/Tethering( 1044): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1044):  ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1044): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1044):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1163645
E/WifiStateMachine( 1044):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1163645
E/WifiStateMachine( 1044):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1163646
E/WifiConfigStore( 1044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1044): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1044): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1044): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1044): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1044): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1044): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1044): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1044): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1044): doBoolean: SET ps 1
D/WifiNative-wlan0( 1044): SET ps 1: returned true
D/DhcpStateMachine( 1044): RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1044): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1044): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  311): Clearing all IP addresses on wlan0
,I/ActivityManager( 1044): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7579 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2124): Read error: ssl=0xaf4d5600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2124): SSL shutdown failed: ssl=0xaf4d5600: I/O error during system call, Broken pipe
E/WifiStateMachine( 1044): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=1163823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=1163823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=1163824  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20( 1044): hidePasspointNotification off =false
D/ConnectivityService( 1044): ignoring duplicate network state non-change
D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1044): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Checking http://clients3.google.com/generate_204 on <unknown ssid>
V/WfdStateTracker( 1943): handleWifiStateChangedEvent: 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiHS20( 1044): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1044): hidePasspointNotification off =false
,W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=1163873  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1044):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNetworkAgent( 1044): NetworkAgent: NetworkAgent channel lost
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateSCANNING
D/ConnectivityService( 1044): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1044): disableDataServiceNotify
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1044): stop dsqn bin
D/DSQN    ( 1044): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1044): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1044): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Disconnected - quitting
D/CSLegacyTypeTracker( 1044): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1044): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1044): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ResourcesManager( 7579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7579): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/LocSvc_java( 1044): Sending msg: 4 arg1:0 arg2:1
W/ResourcesManager( 7579): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524292
W/ResourcesManager( 7579): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/ConnectivityService( 1044): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1044): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1044): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1044): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 7579): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1044): Removing idletimer
D/WIFI    ( 1044): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1044):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LocSvc_java( 10,44): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1044): getAGpsConnectionInfo connType - 4
W/ResourcesManager( 7579): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings( 1044): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java( 1044): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1044): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1044): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1044): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1044): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1044): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1044): StoppedState
,D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7579): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7579): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7579): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7579): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7579): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7579): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1044): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7622 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6925:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10013/pid_6925/cgroup.procs: No such file or directory
,W/ResourcesManager( 7622): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 7622): init()
,W/ExternalStrings( 7622): load override strings
W/ExternalStrings( 7622): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7622): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7622): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7622): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7622): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7622): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7622): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7622): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7622): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7622): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7622): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7622): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7622): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7622): onCreate
V/Signer  ( 7622): override build config not found
D/Signer  ( 7622): value of property debug is false
,D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7622): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7622): Create singleton instance
D/LGMDMWrapper( 7622): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1044): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7655 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6109:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/art     (  336): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 264us total 16.388ms
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 222us total 11.483ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 220us total 10.416ms
I/QRemote ( 6498): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6498): android.os.DeadObjectException
W/System.err( 6498): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6498): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6498): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6498): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6498): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6498): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6498): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6498): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6498): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6498): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6498): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6498): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6498): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6498): android.os.DeadObjectException
W/System.err( 6498): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6498): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6498): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6498): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6498): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6498): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6498): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6498): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6498): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6498): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6498): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6498): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6498): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6498): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/ActivityThread( 7622): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1044): failed to open /acct/uid_1000/pid_6109/cgroup.procs: No such file or directory
W/ActivityManager( 1044): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6498): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6498): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1044): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7679 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6498): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/PCSuite ( 7655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7655): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/UEI.SmartControl( 7679): Quickset Services start...
I/UEI.SmartControl( 7679): Manufacture = LGE
D/UEI.SmartControl( 7679): Id = LGNevo
D/UEI.SmartControl( 7679): File observer start...
,E/UEI.SmartControl( 7679): IR Port is disabled: false
D/UEI.SmartControl( 7679): Starting file observer...
D/UEI.SmartControl( 7679): Extracting JNI libs...
D/UEI.SmartControl( 7679): --- this system supports 32-bit or 64-bit only
D/LgDataFeature( 7579): LgDataFeature() Constructor: none
,D/LgDataFeature( 7579): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LgDataFeature( 7622): LgDataFeature() Constructor: none
D/LgDataFeature( 7622): LgDataFeature() Constructor Done, null
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7655): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
,D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7655): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/UEI.SmartControl( 7679): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/UEI.SmartControl( 7679): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7679): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
I/ActivityManager( 1044): Killing 6760:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
I/UEI.SmartControl( 7679): --- Selecting new region: 6
,I/UEI.SmartControl( 7679): Model = LG-D855
W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/UEI.SmartControl( 7679): QS Service created
W/libprocessgroup( 1044): failed to open /acct/uid_10085/pid_6760/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 7679): Service initServices...
,D/UEI.SmartControl( 7679): QS start get config
,D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,D/SiteAdvisor( 7622): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/UEI.SmartControl( 7679): Loading JNI Libs...
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{38ad4fd0 type 0 when 1453368962763 android} when 1453368962763
V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{3694f2ce type 0 when 1453368964298 com.android.vending} when 1453368964298
E/WifiStateMachine( 1044):  DisconnectedState CMD_START_SCAN -2 -2 ic=2 proc(ms):0 dur:3249 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1111129] from screen [on:0 period:1670018259]
E/WifiStateMachine( 1044):  ConnectModeState CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:3249 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1670018260]
E/WifiStateMachine( 1044):  DriverStartedState CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:3249 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1670018260]
D/WifiNative-wlan0( 1044): doBoolean: SCAN
D/WifiNative-wlan0( 1044): SCAN: returned false
V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,I/art     ( 1044): Explicit concurrent mark sweep GC freed 54485(2MB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 3.622ms total 149.233ms
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1044): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 2669): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1044): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=36 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1044): couldn't identify event type - WPS-AP-AVAILABLE 
,E/WifiStateMachine( 1044):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
E/WifiStateMachine( 1044):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1044):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
E/WifiStateMachine( 1044):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:3249 bcn=0
D/WifiNative-wlan0( 1044): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=1165748  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=1165751  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7579): Not supported operator for automatic switch
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 2669): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1044): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=39 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=1165858  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=1165859  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1044):  DisconnectedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=1165859
,E/WifiStateMachine( 1044):  ConnectModeState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=1165860
E/WifiStateMachine( 1044):  DriverStartedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=1165860
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=1165861
E/WifiStateMachine( 1044):  DefaultState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=1165861
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=1165862  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2669): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2669): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1044): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1044): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Tethering( 1044): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=1165871  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
I/UEI.SmartControl( 7679): Supports setup maps: true
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1044):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=1165881  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=1165881  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1044):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=1165882
E/WifiStateMachine( 1044):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=1165882
D/WifiNative-wlan0( 1044): doString: [STATUS]
D/UEI.SmartControl( 7679): QS start statue = true Error code = 0
I/UEI.SmartControl( 7679): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7679): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7679): ### init IR Blaster...
D/WifiMonitor( 1044): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1044): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1044):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1044): setVHTCapabilityType  : false
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/serial_port( 7679): Configuring serial port
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1044): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1044): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 3.
E/UEI.SmartControl( 7679): UEIBLaster setting for 616
I/UEI.SmartControl( 7679): Setting serial record hearder size = 2
I/UEI.SmartControl( 7679): configuring settings for MAXQ616
I/UEI.SmartControl( 7679): Get version...
D/ConnectivityService( 1044): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 1044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1044): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1044): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1044): NetworkAgent connected
D/WifiNative-wlan0( 1044): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1044): doBoolean: SAVE_CONFIG
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1044): SAVE_CONFIG: returned true
E/WifiConfigStore( 1044): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1044): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1044): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1044): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1044): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1044): Start Dhcp Watchdog 2
,D/DhcpStateMachine( 1044): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1044): WaitBeforeStartState
E/WifiStateMachine( 1044):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=1165926  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=1165927  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=1165927  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1044):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UEI.SmartControl( 7679): serial port data available: 21
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1044):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=1165931  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=1165931  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=1165931  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1044):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1044): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7579): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7579): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7579): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7579): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7579): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7579): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7579): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1044): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1044): doBoolean: SET ps 0
D/WifiNative-wlan0( 1044): SET ps 0: returned true
D/WifiNative-wlan0( 1044): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1044): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1044): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1044): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1044): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1044): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f35b8bc target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1044): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f35b8bc target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1044): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1044): DHCP Start wake lock is acquired.
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1044): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1044): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1044): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1044):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1044):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1044):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1044): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1044): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1044): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1044): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1044): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2669): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1044): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1044): doBoolean: SET ps 1
D/WifiNative-wlan0( 1044): SET ps 1: returned true
D/UEI.SmartControl( 7679): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7679): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7679): QS saving settings...
,D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/UEI.SmartControl( 7679): IR Blaster version: 25672567
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1044):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1044):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1044): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1044): ignoring duplicate network state non-change
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1044): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1044): Adding iface wlan0 to network 101
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1044): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1044): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1943): handleWifiStateChangedEvent: 1
D/UEI.SmartControl( 7679): serial port data available: 4
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1044): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1044): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1044): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1044): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1044): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1044): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/ConnectivityService( 1044): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  311): netlink response contains error (File exists)
D/ConnectivityService( 1044): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService( 1044): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1044): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1044): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1044): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1044): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1044): currentScore = 0, newScore = 20
D/ConnectivityService( 1044):    accepting network in place of null
D/ConnectivityService( 1044): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1044): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1044): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1044): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1044): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1044): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1044): validation of new default Network = false
D/ConnectivityService( 1044): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1044): enableDataServiceNotify 
D/DSQN    ( 1044): start dsqn bin
D/LocSvc_java( 1044): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1044): getAGpsConnectionInfo connType - 4
D/WIFI    ( 1044): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1044): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1044): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1044):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1044): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7722): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7722): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
V/NetworkPolicy( 1044): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7722): DSQN ssw
W/ContextImpl( 7679): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/UEI.SmartControl( 7679): Services init done
D/UEI.SmartControl( 7679): QS Service init finished
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UEI.SmartControl( 7679): QS Service version name: 2.1.91
D/UEI.SmartControl( 7679): QS Service version code: 201091
D/UEI.SmartControl( 7679): Service requested: Control
I/UEI.SmartControl( 7679): Device manager: loading config....
D/UEI.SmartControl( 7679): ----------- loading internal config...
E/UEI.SmartControl( 7679): Loading SETTINGS...
,D/UEI.SmartControl( 7679): Request IControl service: devices are loaded...
,I/QRemote ( 6498): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7679): ------ IControl API: 11
I/UEI.SmartControl( 7679): Registering callback...
D/UEI.SmartControl( 7679): Internal service binding...
D/UEI.SmartControl( 7679): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7679): ------ IControl API: 19
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/UEI.SmartControl( 7679): Registering Services Ready callback...
I/UEI.SmartControl( 7679): Notify client services are ready...
I/QRemote ( 6498): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6498): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6498): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6498): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6498): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7679): ------ IControl API: 8
D/QRemote ( 6498): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6498): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6498): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6498): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6498): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6498): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/UEI.SmartControl( 7679): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7679): -----service ready thread exits
I/QRemote ( 6498): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6498): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6498): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6498): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6498): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
,D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6498): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1044): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1044): start to monitor internet connection
D/PCSuite ( 7655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 09:36:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453368964830], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453368964813]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1044): Validated
D/ConnectivityService( 1044): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1044):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1044): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1044): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1044): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1044): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1044):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6498): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6498): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6498): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7655): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7655): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7579): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7579): MCCMNC not supported: null
D/QRemote ( 6498): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6498): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6498): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6498): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6498): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6498): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6498): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453368964874]
I/ActivityManager( 1044): Killing 6954:com.google.android.talk/u0a72 (adj 15): empty #17
,D/QRemote ( 6498): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
D/DhcpStateMachine( 1044): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1044): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1044): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7733): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7733): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7733): version 5.5.6 starting
,E/dhcpcd  ( 7733): get_duid: m
D/dhcpcd  ( 7733): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7733): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup( 1044): failed to open /acct/uid_10072/pid_6954/cgroup.procs: No such file or directory
,V/QRemote ( 6498): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6498): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6498): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6498): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/dhcpcd  ( 7733): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7733): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7733): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7733): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7733): wlan0: sending REQUEST (xid 0x84e396d9), next in 3.75 seconds
,D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1044): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1044): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1044): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7045): onReceive
D/AppUp4:CustFacade( 7045): Context : android.app.ReceiverRestrictedContext@3c1ab89d
D/AppUp4:CustFacade( 7045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7045): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7045): begin check event
I/AppUp4:CustModeStarterReceiver( 7045): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7045): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7045): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7045): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7045): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 2745): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4105): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 2745): DownloadService onCreate
I/DownloadManager( 2745): in removeSpuriousFiles
I/LGDMClient( 4105): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@2e174a96 on behalf of 2745
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 2745): in trimDatabase
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@3ea8a617 on behalf of 2745
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/WifiStateMachine( 1044):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1044):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1044):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1044):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1044):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1044): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1044): identical MTU - not setting
D/Nat464Xlat( 1044): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1044): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1044):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1044): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524295
I/ActivityManager( 1044): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7770 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 2745): DownloadService onStartCommand
V/DownloadManager( 2745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@27757a22 on behalf of 2745
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/GpsLocationProvider( 1044): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1044): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1044): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LGDMClient( 4105): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4105): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4105): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 2745): processing inserted download 1
V/DownloadManager( 2745): processing inserted download 4
V/DownloadManager( 2745): processing inserted download 7
V/DownloadManager( 2745): processing inserted download 8
V/DownloadManager( 2745): processing inserted download 9
V/DownloadManager( 2745): processing inserted download 10
V/DownloadManager( 2745): processing inserted download 16
V/DownloadManager( 2745): processing inserted download 17
V/DownloadManager( 2745): processing inserted download 18
V/DownloadManager( 2745): processing inserted download 21
V/DownloadManager( 2745): processing inserted download 22
,V/DownloadManager( 2745): DownloadService onDestroy
W/ResourcesManager( 7770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7770): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7770): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7770): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7770): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7770): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7770): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7770): LgDataFeature() Constructor: none
D/LgDataFeature( 7770): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7733): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7733): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7733): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7733): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7733): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 7733): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7733): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7733): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7733): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/eas_req ( 7770): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1044): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7812 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7770): JNI_OnLoad()
I/HubEmail( 7770): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7770): registerNatives()
I/HubEmail( 7770): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7770): registerNativeMethods()
I/HubEmail( 7770): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7770): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1044): Killing 7081:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10019/pid_7081/cgroup.procs: No such file or directory
W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = false
D/DhcpStateMachine( 1044): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1044): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1044): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1044): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1044): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1044): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1044): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1044): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1044): RunningState
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1044): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7846 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7812): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7812): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1044): Killing 7104:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10027/pid_7104/cgroup.procs: No such file or directory
,I/ActivityManager( 1044): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7870 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 7124:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10080/pid_7124/cgroup.procs: No such file or directory
,I/ActivityManager( 1044): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7887 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 6808:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_10097/pid_6808/cgroup.procs: No such file or directory
,I/art     ( 7887): Almond Protected OAT
,D/WeatherApplication( 7887): removeAccount
D/WeatherApplication( 7887): Account.length = 0
E/WeatherApplication( 7887): OPERATOR:OPEN
,D/WeatherAncestor( 7887): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:7
D/Weather.Utils( 7887): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7887): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7887): 2 : This is isUpdating : false
D/WeatherAncestor( 7887): connectivity changed - connection : true
,D/WeatherService( 7887): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7887): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7887): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7887): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7887): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7887): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:7
,I/ActivityManager( 1044): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7908 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1044): Killing 7181:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_10005/pid_7181/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,V/WifiInternetCheck( 1044): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1044): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1044): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1044): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1044): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7908): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7908): Loading: webviewchromium
I/LibraryLoader( 7908): Time to load native libraries: 5 ms (timestamps 9054-9059)
,I/LibraryLoader( 7908): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7908): Binding Chromium to main looper Looper (main, tid 1) {3c26df4b}
I/LibraryLoader( 7908): Expected native library version number "",actual native library version number ""
I/chromium( 7908): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7908): Initializing chromium process, renderers=0
,W/art     ( 7908): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  315): registerClient() client 0xb1427440, uid 10093
,W/chromium( 7908): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7908): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7908): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 7908): Requires BLUETOOTH permission
I/Adreno-EGL( 7908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7908): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7908): Build Date: 12/12/14 금
I/Adreno-EGL( 7908): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7908): Remote Branch: 
I/Adreno-EGL( 7908): Local Patches: 
I/Adreno-EGL( 7908): Reconstruct Branch: 
,I/NSApplication( 7908): Starting up...
,I/ActivityManager( 1044): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7969 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1044): Killing 7218:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1044): failed to open /acct/uid_10005/pid_7218/cgroup.procs: No such file or directory
,W/ResourcesManager( 7969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7045): onReceive
D/AppUp4:CustFacade( 7045): Context : android.app.ReceiverRestrictedContext@3c1ab89d
D/AppUp4:CustFacade( 7045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7045): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7045): begin check event
I/AppUp4:CustModeStarterReceiver( 7045): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 2745): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 2745): DownloadService onCreate
D/LGDMClient( 4105): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 2745): in removeSpuriousFiles
I/GLSActivity( 2124): [ac] getting account id
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 4105): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@3c07a270 on behalf of 2745
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 2745): in trimDatabase
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@3595166e on behalf of 2745
,V/DownloadManager( 2745): DownloadService onStartCommand
V/DownloadManager( 2745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@b1c759c on behalf of 2745
I/GLSUser ( 2124): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 2745): processing inserted download 1
V/DownloadManager( 2745): processing inserted download 4
V/DownloadManager( 2745): processing inserted download 7
,V/DownloadManager( 2745): processing inserted download 8
V/DownloadManager( 2745): processing inserted download 9
V/DownloadManager( 2745): processing inserted download 10
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 2745): processing inserted download 16
E/LGDMClient( 4105): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4105): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4105): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = false
,W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7887): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:8
V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 2745): processing inserted download 17
W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 2745): processing inserted download 18
V/DownloadManager( 2745): processing inserted download 21
V/DownloadManager( 2745): processing inserted download 22
W/Kids    ( 2333): [AccountUtils] Account not ready
W/Kids    ( 2333): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2333): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2333): 	at java.lang.Thread.run(Thread.java:818)
D/Weather.Utils( 7887): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7887): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7887): 2 : This is isUpdating : false
D/WeatherAncestor( 7887): connectivity changed - connection : true
D/WeatherService( 7887): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1db1bc5e
D/ForecastDataCache( 7887): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7887): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7887): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7887): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7887): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:8
D/LgeQuickCoverNLService( 1402): onNotificationPosted
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
V/DownloadManager( 2745): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7622): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7045): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7045): onReceive
V/FormManager( 7812): There are no updated forms. The schedule will be deleted.
V/FormManager( 7812): Alarm would be updated, because LastCheckTime has been updated.
,D/AppUp4:CustFacade( 7045): Context : android.app.ReceiverRestrictedContext@3c1ab89d
D/AppUp4:CustFacade( 7045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7045): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7045): begin check event
I/AppUp4:CustModeStarterReceiver( 7045): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 2745): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4105): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 2745): DownloadService onCreate
I/DownloadManager( 2745): in removeSpuriousFiles
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4105): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4105): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
I/LgeMiscReceiver( 3310): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3310): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3310): networkInfo.isConnected() = true
D/PhoneState( 3310): setPdpRejectCasuse : false
,W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Kids    ( 2333): [AccountUtils] Account not ready
W/Kids    ( 2333): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2333): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2333): 	at java.lang.Thread.run(Thread.java:818)
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
W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
E/LGDMClient( 4105): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4105): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4105): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/WeatherAncestor( 7887): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:8
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/Weather.Utils( 7887): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7887): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7887): 2 : This is isUpdating : false
D/WeatherAncestor( 7887): connectivity changed - connection : true
D/WeatherService( 7887): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1db1bc5e
D/ForecastDataCache( 7887): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7887): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7887): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7887): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7887): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:8
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 1044): Explicit concurrent mark sweep GC freed 67252(3MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 1.424ms total 103.610ms
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@26002b7a on behalf of 2745
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2745): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,V/FormManager( 7812): There are no updated forms. The schedule will be deleted.
V/DownloadManager( 2745): DownloadService onStartCommand
V/FormManager( 7812): Alarm would be updated, because LastCheckTime has been updated.
I/DownloadManager( 2745): in trimDatabase
V/DownloadManager( 2745): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2745): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@1fa27d21 on behalf of 2745
,V/DownloadManager( 2745): created cursor android.database.sqlite.SQLiteCursor@22d58546 on behalf of 2745
,V/DownloadManager( 2745): processing inserted download 1
V/DownloadManager( 2745): processing inserted download 4
V/DownloadManager( 2745): processing inserted download 7
V/DownloadManager( 2745): processing inserted download 8
V/DownloadManager( 2745): processing inserted download 9
,V/DownloadManager( 2745): processing inserted download 10
V/DownloadManager( 2745): processing inserted download 16
V/DownloadManager( 2745): processing inserted download 17
V/DownloadManager( 2745): processing inserted download 18
V/DownloadManager( 2745): processing inserted download 21
V/DownloadManager( 2745): processing inserted download 22
,V/DownloadManager( 2745): DownloadService onDestroy
I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
W/Kids    ( 2333): [AccountUtils] Account not ready
W/Kids    ( 2333): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2333): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2333): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1044): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 7679): Internal timer expired: 1
,D/UEI.SmartControl( 7679): unbind internal service
D/serial_port( 7679): close(fd = 25)
,I/UEI.SmartControl( 7679): Serial port is closed.
V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{10c08598 type 2 when 1173319 com.google.android.gms} when 1173319
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2124): Connected
,D/GCM     ( 2124): Message class com.google.f.a.a.p
I/GAV4    ( 7908): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1044): Killing 6640:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1044): failed to open /acct/uid_10054/pid_6640/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1177969578303; DSPS: 38741803; Offset : -4351884524
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{3db52c2d type 0 when 1453368984658 com.android.vending} when 1453368984658
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 4.
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1197972267931; DSPS: 39397251; Offset : -4351880365
,E/WifiStateMachine( 1044):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1044):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1044):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1044):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1044):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1044):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1217974118237; DSPS: 40052671; Offset : -4351861191
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{3e692574 type 0 when 1453369005615 com.android.vending} when 1453369005615
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Scheduling replication attempt 5.
,I/UsageStatsService( 1044): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1237976186770; DSPS: 40708099; Offset : -4351867905
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): RTC_WAKEUP set : Alarm{d18b237 type 0 when 1453369038758 com.android.vending} when 1453369038758
,D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,V/SIM_STK ( 1044): Menu title from STK is T-Mobile
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7142): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7142): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7142): [1] 5.onFinished: Giving up after 6 failures.
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{33436c41 type 2 when 1243696 android} when 1243696
,I/ActivityManager( 1044): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=8085 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 8085): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 8085): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 8085): Created application version: 3.2.35 (30235)
,I/BooksSync( 8085): Starting books sync
,D/BooksSync( 8085): started syncMyEbooks
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
,D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8085): Authentication error
E/BooksAccountManager( 8085): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 8085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 8085): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 8085): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 8085): Error response from books API: {
W/ApiaryClient( 8085):  "error": {
W/ApiaryClient( 8085):   "errors": [
W/ApiaryClient( 8085):    {
W/ApiaryClient( 8085):     "domain": "global",
W/ApiaryClient( 8085):     "reason": "required",
W/ApiaryClient( 8085):     "message": "Login Required",
W/ApiaryClient( 8085):     "locationType": "header",,
W/ApiaryClient( 8085):     "location": "Authorization"
W/ApiaryClient( 8085):    }
W/ApiaryClient( 8085):   ],
W/ApiaryClient( 8085):   "code": 401,
W/ApiaryClient( 8085):   "message": "Login Required"
W/ApiaryClient( 8085):  }
W/ApiaryClient( 8085): }
,W/ApiaryClient( 8085): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8085): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4322395197275793555&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8085): Headers:
W/ApiaryClient( 8085): accept-encoding: [gzip]
W/ApiaryClient( 8085): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 8085): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8085): Authentication error
E/BooksAccountManager( 8085): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 8085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 8085): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 8085): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 8085): Error response from books API: {
W/ApiaryClient( 8085):  "error": {
W/ApiaryClient( 8085):   "errors": [
W/ApiaryClient( 8085):    {
W/ApiaryClient( 8085):     "domain": "global",
W/ApiaryClient( 8085):     "reason": "required",
W/ApiaryClient( 8085):     "message": "Login Required",
W/ApiaryClient( 8085):     "locationType": "header",
W/ApiaryClient( 8085):     "location": "Authorization"
W/ApiaryClient( 8085):    }
W/ApiaryClient( 8085):   ],
W/ApiaryClient( 8085):   "code": 401,
W/ApiaryClient( 8085):   "message": "Login Required"
W/ApiaryClient( 8085):  }
W/ApiaryClient( 8085): }
,W/ApiaryClient( 8085): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8085): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4322395197275793555&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8085): Headers:
W/ApiaryClient( 8085): accept-encoding: [gzip]
W/ApiaryClient( 8085): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 8085): gdata-version: 2
V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2124): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2124): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2124): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2124): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2124): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1044): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1044): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1044): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1044): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1044): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
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
W/GLSActivity( 2124): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2124): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2124): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2124): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2124): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 8085): Authentication error
E/BooksAccountManager( 8085): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 8085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 8085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 8085): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 8085): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{3b494f88 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 8085): Error response from books API: {
W/ApiaryClient( 8085):  "error": {
W/ApiaryClient( 8085):   "errors": [
W/ApiaryClient( 8085):    {
W/ApiaryClient( 8085):     "domain": "global",
W/ApiaryClient( 8085):     "reason": "required",
W/ApiaryClient( 8085):     "message": "Login Required",
W/ApiaryClient( 8085):     "locationType": "header",
W/ApiaryClient( 8085):     "location": "Authorization"
W/ApiaryClient( 8085):    }
W/ApiaryClient( 8085):   ],
W/ApiaryClient( 8085):   "code": 401,
W/ApiaryClient( 8085):   "message": "Login Required"
W/ApiaryClient( 8085):  }
W/ApiaryClient( 8085): }
,W/ApiaryClient( 8085): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 8085): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4322395197275793555&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 8085): Headers:
W/ApiaryClient( 8085): accept-encoding: [gzip]
W/ApiaryClient( 8085): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 8085): gdata-version: 2
E/BooksSync( 8085): Soft error: 
E/BooksSync( 8085): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8085): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4322395197275793555&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8085): Headers:
E/BooksSync( 8085): accept-encoding: [gzip]
E/BooksSync( 8085): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 8085): gdata-version: 2
E/BooksSync( 8085): 
E/BooksSync( 8085): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 8085): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 8085): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 8085): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 8085): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 8085): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 8085): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 8085): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 8085): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 8085): {
E/BooksSync( 8085):  "error": {
E/BooksSync( 8085):   "errors": [
E/BooksSync( 8085):    {
E/BooksSync( 8085):     "domain": "global",
E/BooksSync( 8085):     "reason": "required",
E/BooksSync( 8085):     "message": "Login Required",
E/BooksSync( 8085):     "locationType": "header",
E/BooksSync( 8085):     "location": "Authorization"
E/BooksSync( 8085):    }
E/BooksSync( 8085):   ],
E/BooksSync( 8085):   "code": 401,
E/BooksSync( 8085):   "message": "Login Required"
E/BooksSync( 8085):  }
E/BooksSync( 8085): }
E/BooksSync( 8085): 
E/BooksSync( 8085): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 8085): 	... 8 more
,E/BooksSync( 8085): Sync error
E/BooksSync( 8085): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 8085): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4322395197275793555&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 8085): Headers:
E/BooksSync( 8085): accept-encoding: [gzip]
E/BooksSync( 8085): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 8085): gdata-version: 2
E/BooksSync( 8085): 
E/BooksSync( 8085): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 8085): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 8085): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 8085): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 8085): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 8085): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 8085): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 8085): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 8085): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 8085): {
E/BooksSync( 8085):  "error": {
E/BooksSync( 8085):   "errors": [
E/BooksSync( 8085):    {
E/BooksSync( 8085):     "domain": "global",
E/BooksSync( 8085):     "reason": "required",
E/BooksSync( 8085):     "message": "Login Required",
E/BooksSync( 8085):     "locationType": "header",
E/BooksSync( 8085):     "location": "Authorization"
E/BooksSync( 8085):    }
E/BooksSync( 8085):   ],
E/BooksSync( 8085):   "code": 401,
E/BooksSync( 8085):   "message": "Login Required"
E/BooksSync( 8085):  }
E/BooksSync( 8085): }
E/BooksSync( 8085): 
E/BooksSync( 8085): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 8085): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 8085): 	... 8 more
I/BooksSync( 8085): Finished books sync
I/ActivityManager( 1044): Killing 6880:com.lge.clock/u0a10 (adj 15): empty #17
,D/SyncManager( 1044): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1243696, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1044): failed to open /acct/uid_10010/pid_6880/cgroup.procs: No such file or directory
,I/GAV2    ( 8085): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1257978069054; DSPS: 41363521; Offset : -4351877711
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{445f6 type 2 when 1273782 android} when 1273782
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1277980716599; DSPS: 42018968; Offset : -4351885195
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1297985166747; DSPS: 42674473; Offset : -4351860018
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1317987250125; DSPS: 43329902; Offset : -4351882327
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1337989127565; DSPS: 43985323; Offset : -4351866511
,D/PowerManagerServiceEx( 1044): acquireWakeLockInternal: lock=651392314, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,V/AlarmManager( 1044): ELAPSED_WAKEUP set : Alarm{2166edf7 type 2 when 1340270 android} when 1340270
D/[Concierge]Service( 2577): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1044): releaseWakeLockInternal: lock=651392314 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1357991789954; DSPS: 44640770; Offset : -4351859178
,D/sensors_hal_Time( 1044): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1044): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1044): tsOffsetIs: Apps: 1377993831926; DSPS: 45296198; Offset : -4351892323
,TIME-OUT KILL (timeout was 1200000ms)
```
