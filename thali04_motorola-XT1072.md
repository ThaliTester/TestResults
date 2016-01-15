#### Test 561517803567b2a_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 6560): 
D/AndroidRuntime( 6560): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6560): CheckJNI is OFF
D/AndroidRuntime( 6560): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6579 uid=10450 gids={50450, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6560): Shutting down VM
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.230ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.497ms
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.470ms
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6579): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6579): Time to load native libraries: 2 ms (timestamps 6384-6386)
I/LibraryLoader( 6579): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6579): Binding Chromium to main looper Looper (main, tid 1) {399018b4}
I/LibraryLoader( 6579): Expected native library version number "",actual native library version number ""
I/chromium( 6579): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6579): Initializing chromium process, singleProcess=true
W/art     ( 6579): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6579): ApplicationContext is null in ApplicationStatus
W/chromium( 6579): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6579): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6579): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6579): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6579): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6579): Local Branch: 
I/Adreno-EGL( 6579): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6579): Local Patches: NONE
I/Adreno-EGL( 6579): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
W/ActivityManager(  882): Activity pause timeout for ActivityRecord{39a1e7c4 u0 com.test.thalitest/.MainActivity t6}
D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4379feb:true
I/art     (  882): Explicit concurrent mark sweep GC freed 40417(1964KB) AllocSpace objects, 2(216KB) LOS objects, 33% free, 20MB/30MB, paused 1.471ms total 131.678ms
,W/art     ( 6579): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6579): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6579): CordovaWebView is running on device made by: motorola
,W/art     ( 6579): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6579): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6579): Render dirty regions requested: true
D/Atlas   ( 6579): Validating map...
W/chromium( 6579): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6579): Initialized EGL, version 1.4
D/OpenGLRenderer( 6579): Enabling debug mode 0
I/Keyboard.Facilitator( 1420): onFinishInput()
I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1164
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s54ms (total +1s164ms)
W/IInputConnectionWrapper( 6579): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6579): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6579): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6579): Cannot call determinedVisibility() - never saw a connection for the pid: 6579
D/JsMessageQueue( 6579): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6579): JniHelper::setJavaVM(0xb7dc3310), pthread_self() = -1206564224
,I/chromium( 6579): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6579): Initializing JXcore engine
W/jxcore-log( 6579): JXcore engine is ready
,W/Thread-793( 6642): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10450 path="socket:[5771]" dev="sockfs" ino=5771 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-793( 6642): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10450 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-793( 6642): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10450 path="socket:[7410]" dev="sockfs" ino=7410 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-793( 6642): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10450 path="socket:[30650]" dev="sockfs" ino=30650 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 6579): Starting JXcore engine
,W/jxcore-log( 6579): Platform android
W/jxcore-log( 6579): 
,W/jxcore-log( 6579): Process ARCH arm
W/jxcore-log( 6579): 
,I/jxcore-log( 6579): JXcore Cordova bridge is ready!
I/jxcore-log( 6579): 
,W/jxcore-log( 6579): JXcore engine is started
,I/jxcore-log( 6579): Toggling radios to true
I/jxcore-log( 6579): 
,D/BluetoothAdapter( 6579): enable(): BT is already enabled..!
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=6579, uid=10450
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6579): Radios toggled
I/jxcore-log( 6579): 
,I/jxcore-log( 6579): My device name is: motorola-XT1072
I/jxcore-log( 6579): 
,I/wpa_supplicant( 1392): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295):  STA Disconnected !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  295): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1392): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1392): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  882): InitialState.processMessage what=4
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1392): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  292): Clearing all IP addresses on wlan0
D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 21
D/TCMD    (  478): Listening for incoming client connection request
,V/NativeCrypto( 1746): Read error: ssl=0xb80f44d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1746): SSL shutdown failed: ssl=0xb80f44d0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  882): connected time updated 120861
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6668 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
E/wpa_supplicant( 1392): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  882): Start Disconnecting Watchdog 1
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/wpa_supplicant( 1392): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): ConnectModeState: Network connection lost 
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1392): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  292): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6668): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6695 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6317:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_6317/cgroup.procs: No such file or directory
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  478): NL - Read 56 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1392): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  882): [1,452,855,719,388 ms] noteScanEnd no scan source
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1392): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b4e3028 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/TCMD    (  478): NL - Read 312 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 192 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
I/wpa_supplicant( 1392): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1392): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1392): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
E/MDMCTBK (  295): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  295): get_freq !!, resp=2412
I/MDMCTBK (  295): get_freq !!, Strip data
I/MDMCTBK (  295): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1211945704
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  292): Setting iface cfg
E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 1392): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1392): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23242f8f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23242f8f target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6695): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6695): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6695): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6695): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6695): MmsConfig.loadFromResources
E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6695): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6695): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6695): startup - clean
,I/Babel   ( 6695): deleted: false for 0
,E/DHCPCD  ( 6734): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6734): version 5.5.6 starting
E/DHCPCD  ( 6734): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6734): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6734): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6695): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6695): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6695): Unsupported profile 4 for video/mp4v-es
,D/DHCPCD  ( 6734): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6734): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6734): wlan0: sending REQUEST (xid 0xdd28a4d6), next in 3.94 seconds
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 6360:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6360/cgroup.procs: No such file or directory
,I/vclib   ( 6695): onServiceConnected
,W/Babel   ( 6695): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6734): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6734): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6734): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6734): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6734): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6734): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 20
D/TCMD    (  478): Listening for incoming client connection request
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/DHCPCD  ( 6734): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 11:02:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452855721636], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452855721617]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6797 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Tethering(  882): MasterInitialState.processMessage what=3
,D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1476): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2536): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2536): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2536): [debug] > CusSM.onRadioDown
,E/global frequency( 2536): no tags to log
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 55554(3MB) AllocSpace objects, 35(1221KB) LOS objects, 39% free, 7MB/12MB, paused 838us total 46.589ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/MusicStore( 6797): Database version: 120
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/ResourcesManager( 6797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 1476): Explicit concurrent mark sweep GC freed 4330(180KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 877us total 30.896ms
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ActivityThread( 6797): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c0a3a10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6797): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6797): GMSCore installation verified
,I/ConfigStore( 6797): Config Database version: 1
,I/art     (  882): Explicit concurrent mark sweep GC freed 44427(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.640ms total 130.108ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/MediaRouter( 6797): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6797): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6797): type=WIFI subType= reason=null isConnected=true
,I/art     ( 2536): Explicit concurrent mark sweep GC freed 13344(730KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 1.150ms total 103.487ms
I/NetworkMonitor( 6797): type=WIFI subType= reason=null isConnected=true
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6837 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2536): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
I/GHttpClientFactory( 6797): Using our fixed implementation of GMSCore's GoogleHttpClient
D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2536): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2536): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/GoogleURLConnFactory( 6797): Using platform SSLCertificateSocketFactory
,D/Checkin ( 2536): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/ActivityManager(  882): Killing 6392:android.process.acore/u0a7 (adj 15): empty #7
,I/global frequency( 2536): BcsDSCheckin.events found events 196
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6392/cgroup.procs: No such file or directory
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,V/Mms     ( 6837): mnc/mcc: 
,V/Mms     ( 6837): tag: int value: recipientLimit - 20
V/Mms     ( 6837): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6837): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6837): tag: int value: maxSubjectLength - 80
V/Mms     ( 6837): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6837): tag: bool value: enableGroupMms - false
,V/Mms     ( 6837):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MMApiWSBase( 2536): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6866 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6238:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_6238/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {3a49aa5a, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {3a638b62, *walarm*:com.google.android.intent.action.SEND_IDLE}
,D/PhoneMonitor( 6866): Register our PhoneStateListener
,V/AlarmManager(  882): done {3a49aa5a, *alarm*:android.intent.action.TIME_TICK} [78ms]
,D/MobileConnectivityChangeReceiver( 6866): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6866): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6695:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6695/cgroup.procs: No such file or directory
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855643422 min interval config: 0 actual interval: 80560
I/CheckinService( 6451): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6451): SYNC; picasa accounts
,D/NetworkLogImpl( 6451): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6451): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 6451): Checking schedule, now: 1452855724054 next: 1452855673406
I/CheckinService( 6451): active receiver: enabled
,I/iu.UploadsManager( 6451): num queued entries: 0
I/iu.UploadsManager( 6451): num updated entries: 0
I/iu.SyncManager( 6451): NEXT; no task
,I/CheckinService( 6451): Preparing to send checkin request
,I/EventLogService( 6451): Accumulating logs since 1452855640309
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6909 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6451): Checkin reason type: 8 attempt count: 1
,D/WifiService(  882): New client listening to asynchronous messages
,E/ActivityThread( 6451): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): now: 196412 ,futureTime: 9223372036854775807
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): now: 196412 ,futureTime: 9223372036854775807
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): now: 196412 ,futureTime: 9223372036854775807
D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6797): type=WIFI subType= reason=null isConnected=true
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/MMApiWSBase( 2536): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2536): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2536): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/art     (  882): Explicit concurrent mark sweep GC freed 9676(466KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.144ms total 129.394ms
,D/Central_PollingManager( 1476): now: 196466 ,futureTime: 86473892
D/Central_PollingManager( 1476): Polling alarm set to expire at: 86473892 Current Time: 196466
D/OtaApp  ( 2536): [debug] > PollingManagerService, now: 196466 ,futureTime: 25332611
,D/OtaApp  ( 2536): [debug] > Polling alarm set to expire at: 25332611 Current Time: 196466
,D/OtaApp  ( 2536): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2536): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2536): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/global frequency( 2536): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2536): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2536): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CheckinProvider(  882): 196 events delete 0 left
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 3504(145KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 594us total 27.674ms
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,I/global frequency( 2536): BcsDSCheckin.events found events 0
D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6933 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6950 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6933): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6950): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6950): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6950): VM with version 2.1.0 has multidex support
I/MultiDex( 6950): install
I/MultiDex( 6950): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6950): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6950): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6950): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e2d85f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6950): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6933): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6933): MmsConfig.loadMmsSettings
I/Babel_SMS( 6933): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6933): MmsConfig.loadFromDatabase
,I/art     ( 6950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/DataUsage( 2536): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,E/Babel_SMS( 6933): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6933): MmsConfig.loadFromResources
,E/Babel_SMS( 6933): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6933): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6933): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6933): startup - clean
,D/NativeLibraryUtils( 6950): Install completed successfully. count=14 extracted=0
,I/Babel   ( 6933): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6980 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  297): Instantiating CDM.
I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,W/VideoCapabilities( 6933): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6933): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6933): Unsupported mime video/mpeg2
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb13b8960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7df66c8, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7df3d28, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f248e0, idLength=0xb55a2730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=2198058948
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7dee1f0
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7dde8d0, signature_length=3042584340
,I/VideoCapabilities( 6933): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6933): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6933): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6933): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6933): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6933): onServiceConnected
,W/Babel   ( 6933): Attempted to change video mute state without an active call.
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 6933): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6668:com.motorola.context/u0a8 (adj 15): empty #7
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb55a2960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7edc1a8, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7df3d28, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f24920, idLength=0xb55a2730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  297): PrepareKeyRequest: nonce=475771397
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7dee1f0
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7e2b1a0, signature_length=3042584340
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_6668/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {dc04ea1, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6980): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6980): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6980): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6980): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6980): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6980):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6980):   adb logcat -s GAv4
,W/GAv4    ( 6980): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,W/GAv4    ( 6980): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6980): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6980): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6980): Time to load native libraries: 1 ms (timestamps 8248-8249)
,I/LibraryLoader( 6980): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6980): Binding Chromium to main looper Looper (main, tid 1) {3cdacd61}
I/LibraryLoader( 6980): Expected native library version number "",actual native library version number ""
I/chromium( 6980): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6980): Initializing chromium process, singleProcess=true
,W/art     ( 6980): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6980): ApplicationContext is null in ApplicationStatus
,W/chromium( 6980): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6980): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6980): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6980): Local Branch: 
I/Adreno-EGL( 6980): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6980): Local Patches: NONE
I/Adreno-EGL( 6980): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6980): Requires BLUETOOTH permission
,I/NSApplication( 6980): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7048 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6797:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/WVCdm   (  297): CdmEngine::CloseSession
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6797/cgroup.procs: No such file or directory
,I/dex2oat ( 7066): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7066): dex2oat took 113.903ms (threads: 4)
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7074 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6837:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 23.492ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.726ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.141ms
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6837/cgroup.procs: No such file or directory
,W/ResourcesManager( 7074): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7099 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Killing 6909:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ContactLocale( 7099): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 6866:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6909/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6866/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7129 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6451): Classify the device as Phone.
,I/MusicStore( 7129): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7129): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6451): Sending checkin request (9576 bytes)
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7129): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7129): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7129): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7129): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7129): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7129): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c0a3a10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7129): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7129): GMSCore installation verified
,I/ConfigStore( 7129): Config Database version: 1
,I/MediaRouter( 7129): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7129): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7129): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7129): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7174 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6426): Explicit concurrent mark sweep GC freed 1480(64KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 380us total 32.269ms
,I/art     (  882): Explicit concurrent mark sweep GC freed 13103(637KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.509ms total 154.500ms
,I/GHttpClientFactory( 7129): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7129): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7174): mnc/mcc: 
V/Mms     ( 7174): tag: int value: recipientLimit - 20
V/Mms     ( 7174): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7174): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7174): tag: int value: maxSubjectLength - 80
V/Mms     ( 7174): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7174): tag: bool value: enableGroupMms - false
,V/Mms     ( 7174):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  882): Killing 6933:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 6451): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6933/cgroup.procs: No such file or directory
,E/ActivityThread( 6451): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7174): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7206 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6980:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7206): Register our PhoneStateListener
,E/libprocessgroup(  882): failed to kill 1 processes for processgroup 6980
,D/MobileConnectivityChangeReceiver( 7206): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7206): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855643422 min interval config: 0 actual interval: 86287
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7230 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7048:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7048/cgroup.procs: No such file or directory
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 6451): Classify the device as Phone.
,I/CheckinTask( 6451): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6451): Checking schedule, now: 1452855730144 next: 1453456867133
I/CheckinService( 6451): active receiver: disabled
,I/CheckinService( 6451): Checking schedule, now: 1452855730173 next: 1453456867133
I/CheckinService( 6451): active receiver: disabled
,D/CheckinService( 6451): Recording last checkin time for package unspecified as 1452855730178
,I/ActivityManager(  882): Killing 7074:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309873, SEQNUM=4435, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-134, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ActivityManager(  882): Killing 7099:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7074/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7099/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7265 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7129:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7129/cgroup.procs: No such file or directory
,W/ResourcesManager( 7265): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7265): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7265): MmsConfig.loadMmsSettings
I/Babel_SMS( 7265): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7265): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7265): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7265): MmsConfig.loadFromResources
E/Babel_SMS( 7265): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7265): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7265): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7265): startup - clean
,I/Babel   ( 7265): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7301 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7265): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7265): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7265): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7265): onServiceConnected
W/Babel   ( 7265): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7301): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7301):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7301):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7301): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7265): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7174:com.android.mms/u0a23 (adj 13): empty #7
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7301): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7301): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7174/cgroup.procs: No such file or directory
,I/WebViewFactory( 7301): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7301): Time to load native libraries: 2 ms (timestamps 4285-4287)
I/LibraryLoader( 7301): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7301): Binding Chromium to main looper Looper (main, tid 1) {3cdacd61}
I/LibraryLoader( 7301): Expected native library version number "",actual native library version number ""
I/chromium( 7301): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7301): Initializing chromium process, singleProcess=true
W/art     ( 7301): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7301): ApplicationContext is null in ApplicationStatus
,W/chromium( 7301): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7301): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7301): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7301): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7301): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7301): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7301): Local Branch: 
I/Adreno-EGL( 7301): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7301): Local Patches: NONE
I/Adreno-EGL( 7301): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7301): Starting up...
,W/AudioManagerAndroid( 7301): Requires BLUETOOTH permission
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7373 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7206:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7206/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7395 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7230:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7230/cgroup.procs: No such file or directory
,W/ResourcesManager( 7395): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7420 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7301:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7420): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  882): failed to kill 1 processes for processgroup 7301
,I/ActivityManager(  882): Killing 7265:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7265/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2536): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2536): bindWebServices(): registering our AIDL callback...
I/SundryService( 2536): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2536): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2536): onServiceConnected()
,V/AlarmManager(  882): done {3a638b62, *walarm*:com.google.android.intent.action.SEND_IDLE} [10376ms]
,D/GetNotificationsWS( 2536): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2536): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2536): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7448 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 24.390ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 32.249ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 19.755ms
,I/MusicStore( 7448): Database version: 120
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7448): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 7448): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7448): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7448): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Launcher( 1565): Deferring update until onResume
,W/ActivityThread( 7448): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7448): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c0a3a10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7448): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7448): GMSCore installation verified
,I/art     (  882): Explicit concurrent mark sweep GC freed 19766(1019KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.778ms total 142.352ms
V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@924c6ca
,I/ConfigStore( 7448): Config Database version: 1
,I/GCoreNlp( 1746): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/MediaRouter( 7448): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7448): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7448): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7448): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7488 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7448): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7448): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  882): Killing 6950:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7488): mnc/mcc: 
V/Mms     ( 7488): tag: int value: recipientLimit - 20
,V/Mms     ( 7488): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7488): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7488): tag: int value: maxSubjectLength - 80
V/Mms     ( 7488): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7488): tag: bool value: enableGroupMms - false
V/Mms     ( 7488):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_6950/cgroup.procs: No such file or directory
,W/ResourcesManager( 7488): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7514 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7373:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7373/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7514): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7514): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7514): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855730178 min interval config: 0 actual interval: 5101
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855730178 min interval config: 0 actual interval: 5107
,I/CheckinService( 6451): Checking schedule, now: 1452855735299 next: 1452855760133
I/CheckinService( 6451): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7537 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6451): Checking schedule, now: 1452855735349 next: 1452855760133
I/CheckinService( 6451): active receiver: disabled
,I/ActivityManager(  882): Killing 7395:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7395/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7557 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7420:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7420/cgroup.procs: No such file or directory
,W/ResourcesManager( 7557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7557): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7557): MmsConfig.loadMmsSettings
I/Babel_SMS( 7557): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7557): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7557): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7557): MmsConfig.loadFromResources
,E/Babel_SMS( 7557): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7557): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/art     ( 7557): Suspending all threads took: 5.965ms
,W/Settings( 7557): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7557): startup - clean
,I/Babel   ( 7557): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7592 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7557): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7557): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7557): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7557): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7557): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7557): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7557): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7557): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7557): onServiceConnected
,W/Babel   ( 7557): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7592): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7592): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7592): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7592):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7592):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7592): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7592): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7592): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7557): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7448:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7592): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7592): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7448/cgroup.procs: No such file or directory
,I/WebViewFactory( 7592): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7592): Time to load native libraries: 1 ms (timestamps 9125-9126)
I/LibraryLoader( 7592): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7592): Binding Chromium to main looper Looper (main, tid 1) {3cdacd61}
I/LibraryLoader( 7592): Expected native library version number "",actual native library version number ""
I/chromium( 7592): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7592): Initializing chromium process, singleProcess=true
W/art     ( 7592): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7592): ApplicationContext is null in ApplicationStatus
,W/chromium( 7592): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7592): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7592): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7592): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7592): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7592): Local Branch: 
I/Adreno-EGL( 7592): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7592): Local Patches: NONE
I/Adreno-EGL( 7592): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7592): Starting up...
,W/AudioManagerAndroid( 7592): Requires BLUETOOTH permission
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7660 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7488:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7488/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7679 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7514:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7514/cgroup.procs: No such file or directory
,W/ResourcesManager( 7679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7703 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7557:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7703): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7537:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7557/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7537/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2536): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2536): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2536): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2536): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2536): onServiceConnected()
D/GetNotificationsWS( 2536): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2536): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2536): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2536): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2536): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2536): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7755 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2536): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2536): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2536): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2536): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2536): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,I/art     (  882): Explicit concurrent mark sweep GC freed 14038(701KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.604ms total 120.247ms
,I/Keyboard.Facilitator( 1420): onFinishInput()
,W/IInputConnectionWrapper( 6579): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,399
,D/WearableService( 1746): callingUid 10016, callindPid: 1746
,E/MDM     ( 1746): [216] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 6451): Restart initialization of location
,D/AuthorizationBluetoothService( 1746): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  882): done {dc04ea1, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [13274ms]
,I/jxcore-log( 6579): Test app app.js loaded
I/jxcore-log( 6579): 
,I/chromium( 6579): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7784 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,W/GCoreFlp( 1746): No location to return for getLastLocation()
W/FusedLocationProvider( 1746): location=null
,D/PhoneMonitor( 7784): Register our PhoneStateListener
,V/SetupWizard( 7784): Connected to Gservices successfully
I/ActivityManager(  882): Killing 7592:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7592/cgroup.procs: No such file or directory
,D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7807 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 329us total 25.538ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.663ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.845ms
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7835 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7852 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7660:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  882): Killing 7679:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7660/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7679/cgroup.procs: No such file or directory
,W/ResourcesManager( 7852): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7852): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7852): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7852): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7852): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7852): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7852): MmsConfig.loadFromResources
E/Babel_SMS( 7852): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7852): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7852): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7852): startup - clean
,I/Babel   ( 7852): deleted: false for 0
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7885 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7852): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7852): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7852): Unsupported mime video/mpeg2
,W/asset   ( 7885): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7885): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7885): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7885): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7852): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7852): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7852): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7852): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7852): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6451): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1565): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e5c4f9e new=com.google.android.velvet.VelvetApplication@e5c4f9e
,I/UpdateIcingCorporaServi( 7807): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6451): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7915 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7852): onServiceConnected
,W/Babel   ( 7852): Attempted to change video mute state without an active call.
,I/Icing   ( 6451): updateResources: need to parse f{com.google.android.gms}
W/ResourcesManager( 7915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7852): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7852): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7807): UpdateCorporaTask done [took 232 ms] updated apps [took 232 ms] 
,I/ActivityManager(  882): Killing 7784:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7852): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7852): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7852): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7784/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7951 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7951): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7951): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7951): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7951): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7951): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7951): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7951): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7951): Skipping gmscore version check
,I/ActivityManager(  882): Killing 7755:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7755/cgroup.procs: No such file or directory
,D/Finsky  ( 7951): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8000 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7835:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7835/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8000): Register our PhoneStateListener
,I/ActivityManager(  882): Killing 7885:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7885/cgroup.procs: No such file or directory
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855730178 min interval config: 0 actual interval: 11351
,D/TaskPersister(  882): removeObsoleteFile: deleting file=5_task.xml
,D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8019 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6451): Checking schedule, now: 1452855741625 next: 1452855760133
I/CheckinService( 6451): active receiver: disabled
,I/Icing   ( 6451): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/art     (  882): Explicit concurrent mark sweep GC freed 12029(571KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.572ms total 129.840ms
,D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Killing 7807:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7807/cgroup.procs: No such file or directory
,D/Icing   ( 6451): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6451): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/CheckinService( 6451): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  882): Killing 7703:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7703/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,W/ProcessCpuTracker(  882): Skipping unknown process pid 8045
W/ProcessCpuTracker(  882): Skipping unknown process pid 8048
,I/ActivityManager(  882): Killing 7915:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7915/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=291, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310596, SEQNUM=4472, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=-145, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310696, SEQNUM=4478, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=10392, POWER_SUPPLY_CHARGE_COUNTER=-137, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1746): disconnect managed GoogleApiClient
,V/AlarmManager(  882): send {55568c5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  882): send {2e7c4f44, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  882): done {55568c5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,V/AlarmManager(  882): done {2e7c4f44, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [30ms]
,I/CheckinService( 6451): Checkin interval check for package: unspecified last checkin: 1452855730178 min interval config: 0 actual interval: 44217
,I/CheckinService( 6451): Checking schedule, now: 1452855774407 next: 1452855760133
I/CheckinService( 6451): active receiver: enabled
,I/CheckinService( 6451): Preparing to send checkin request
I/EventLogService( 6451): Accumulating logs since 1452855724259
,I/CheckinRequestBuilder( 6451): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6451): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8096 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8096): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8096): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8096): VM with version 2.1.0 has multidex support
I/MultiDex( 8096): install
I/MultiDex( 8096): VM has multidex support, MultiDex support library is disabled.
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/JNIHelp ( 8096): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8096): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8096): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e2d85f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8096): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1746): callingUid 10016, callindPid: 1746
,E/MDM     ( 1746): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1746): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6451): Restart initialization of location
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1746): No location to return for getLastLocation()
,W/FusedLocationProvider( 1746): location=null
,I/art     ( 8096): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8096): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8096): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbee5c4e0
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7e5b500, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7df3d28, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f24900, idLength=0xb54a2730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=4191896542
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7dee1f0
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7ef00d8, signature_length=3041535764
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc7000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbee5c4e0
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7ddeb50, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7df3d28, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f24920, idLength=0xb13b8730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1714876898
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7dee1f0
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7ef02c0, signature_length=2973468436
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8133): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8133): dex2oat took 72.250ms (threads: 4)
,I/Adreno-EGL( 8096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8096): Local Branch: 
I/Adreno-EGL( 8096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8096): Local Patches: NONE
I/Adreno-EGL( 8096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8096): Local Branch: 
I/Adreno-EGL( 8096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8096): Local Patches: NONE
I/Adreno-EGL( 8096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8096): Local Branch: 
I/Adreno-EGL( 8096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8096): Local Patches: NONE
I/Adreno-EGL( 8096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8096): Local Branch: 
I/Adreno-EGL( 8096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8096): Local Patches: NONE
I/Adreno-EGL( 8096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6451): Classify the device as Phone.
,I/CheckinTask( 6451): Sending checkin request (9566 bytes)
,I/CheckinRequestBuilder( 6451): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6451): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6451): Classify the device as Phone.
,I/CheckinTask( 6451): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6451): Checking schedule, now: 1452855777214 next: 1453456914210
I/CheckinService( 6451): active receiver: disabled
,D/CheckinService( 6451): Recording last checkin time for package unspecified as 1452855777225
,V/SetupWizard( 8000): Connected to Gservices successfully
,D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Killing 7951:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_7951/cgroup.procs: No such file or directory
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8156 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2174a9ce
,I/GCoreNlp( 1746): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1565): Deferring update until onResume
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/art     ( 1746): Explicit concurrent mark sweep GC freed 102952(5MB) AllocSpace objects, 32(535KB) LOS objects, 40% free, 16MB/26MB, paused 1.237ms total 127.203ms
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8195 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8214 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8019:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 24.278ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.017ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.303ms
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8019/cgroup.procs: No such file or directory
,W/ResourcesManager( 7852): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7852): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8214): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8237 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 8000:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8000/cgroup.procs: No such file or directory
,W/asset   ( 8237): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8237): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8237): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8237): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  882): Explicit concurrent mark sweep GC freed 18395(976KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.427ms total 125.839ms
,D/PackageBroadcastService( 6451): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6451): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8156): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1565): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e5c4f9e new=com.google.android.velvet.VelvetApplication@e5c4f9e
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8271 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6451): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8156): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8296 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8096:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_8096/cgroup.procs: No such file or directory
,D/Finsky  ( 8296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8296): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8296): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8296): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8296): Skipping gmscore version check
,D/Finsky  ( 8296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 8195:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8195/cgroup.procs: No such file or directory
,I/Icing   ( 6451): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6451): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 8237:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_8237/cgroup.procs: No such file or directory
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  882): Killing 7852:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7852/cgroup.procs: No such file or directory
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
,I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1746): onCreate
,I/ConfigService( 1746): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310852, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-136, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311143, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2118, POWER_SUPPLY_CHARGE_COUNTER=-135, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2414): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6579): --= Surplus to requirements =--
I/jxcore-log( 6579): 
I/jxcore-log( 6579): ****TEST TOOK:  ms ****
I/jxcore-log( 6579): 
I/jxcore-log( 6579): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6579): 
,D/AndroidRuntime( 8363): 
D/AndroidRuntime( 8363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8363): CheckJNI is OFF
,D/AndroidRuntime( 8363): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10450 user=-1: uninstall pkg
,I/ActivityManager(  882): Killing 6579:com.test.thalitest/u0a450 (adj 9): stop com.test.thalitest
,W/PackageSettings(  882): Skipping PackageSetting{dcd9135 com.example.hello/10440} due to missing metadata
,D/WifiService(  882): Client connection lost with reason: 4
,I/WindowState(  882): WIN DEATH: Window{21e459db u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  882):   Force finishing activity ActivityRecord{39a1e7c4 u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  882): Spurious death for ProcessRecord{2a976124 6579:com.test.thalitest/u0a450}, curProc for 6579: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10450 user=0: pkg removed
I/ActivityManager(  882):   Force finishing activity ActivityRecord{39a1e7c4 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  882): Duplicate finish request for ActivityRecord{39a1e7c4 u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 2978): Explicit concurrent mark sweep GC freed 10601(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 7MB/12MB, paused 1.446ms total 36.560ms
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1746): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
,I/art     ( 1565): Explicit concurrent mark sweep GC freed 4943(304KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 457us total 104.006ms
,I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
,D/VoicemailCleanupService( 8214): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1420): createOrResetDecoder
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8393 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1746): onCreate
,I/art     (  882): Explicit concurrent mark sweep GC freed 15622(1062KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.129ms total 160.033ms
I/art     (  882): WaitForGcToComplete blocked for 95.330ms for cause Explicit
,W/asset   ( 8393): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8393): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8393): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8415 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  882): removeObsoleteFile: deleting file=6_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
I/ActivityManager(  882): Killing 8156:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
,I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
,I/art     (  882): Explicit concurrent mark sweep GC freed 5037(261KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.571ms total 209.950ms
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8156/cgroup.procs: No such file or directory
,I/Launcher( 1565): Deferring update until onResume
,W/ContextImpl( 8415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6451): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6451): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6451): Reading stored module config
,D/ChimeraCfgMgr( 6451): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6451): Loading module APK com.google.android.play.games
,D/AndroidRuntime( 8363): Shutting down VM
,I/LocationSettingsChecker( 6451): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6451): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6451): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1746): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1746): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6451): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8452 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 6451): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 6451): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 6451): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6451): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6451): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/Launcher( 1565): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e5c4f9e new=com.google.android.velvet.VelvetApplication@e5c4f9e
,D/ChimeraCfgMgr( 6451): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6451): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8479 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/BaseAppContext( 6451): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  882): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6451): CM callback handler got msg 524290
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/BaseAppContext( 6451): Using Auth Proxy for data requests.
,W/DriveInitializer( 6451): Awaiting to be initialized
W/DriveInitializer( 6451): Background init thread started
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8517 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8452): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  882): Killing 8271:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6451): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,E/SQLiteLog( 8452): (778) statement aborts at 18: [DELETE FROM applications WHERE uri=?] 
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8271/cgroup.procs: No such file or directory
E/SQLiteLog( 8452): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=8539 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/native  ( 1420): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1420): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1420): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1420): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SharedPreferencesImpl( 8452): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
,--------- beginning of crash
E/AndroidRuntime( 8452): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 8452): Process: com.google.android.googlequicksearchbox:search, PID: 8452
E/AndroidRuntime( 8452): android.database.sqlite.SQLiteException: cannot rollback - no transaction is active (code 1)
E/AndroidRuntime( 8452): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 8452): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 8452): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:439)
E/AndroidRuntime( 8452): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 8452): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/AndroidRuntime( 8452): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:91)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 8452): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 8452): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 8452): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 8452): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8452): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8452): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 6451): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
