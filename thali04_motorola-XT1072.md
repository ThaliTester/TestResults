#### Test 525354860130a71_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/AndroidRuntime( 6186): 
D/AndroidRuntime( 6186): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6186): CheckJNI is OFF
D/AndroidRuntime( 6186): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  887): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6205 uid=10351 gids={50351, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6186): Shutting down VM
V/ActivityManager(  887): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6205): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6205): Time to load native libraries: 3 ms (timestamps 8023-8026)
,I/LibraryLoader( 6205): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6205): Binding Chromium to main looper Looper (main, tid 1) {15d69d5d}
,I/LibraryLoader( 6205): Expected native library version number "",actual native library version number ""
I/chromium( 6205): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6205): Initializing chromium process, singleProcess=true
W/art     ( 6205): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6205): ApplicationContext is null in ApplicationStatus
,W/chromium( 6205): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6205): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6205): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6205): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6205): Local Branch: 
I/Adreno-EGL( 6205): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6205): Local Patches: NONE
I/Adreno-EGL( 6205): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@309044de:true
,W/ActivityManager(  887): Activity pause timeout for ActivityRecord{24c935eb u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6205): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6205): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6205): CordovaWebView is running on device made by: motorola
,W/art     ( 6205): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6205): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6205): Render dirty regions requested: true
,D/Atlas   ( 6205): Validating map...
,W/chromium( 6205): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6205): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6205): Enabling debug mode 0
,I/Keyboard.Facilitator( 1420): onFinishInput()
,I/LaunchCheckinHandler(  887): Displayed com.test.thalitest/.MainActivity,cp,ca,961
I/ActivityManager(  887): Displayed com.test.thalitest/.MainActivity: +884ms (total +961ms)
,W/IInputConnectionWrapper( 6205): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6205): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6205): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6205): Cannot call determinedVisibility() - never saw a connection for the pid: 6205
D/JsMessageQueue( 6205): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6205): JniHelper::setJavaVM(0xb80b6310), pthread_self() = -1203481096
D/JX-Cordova( 6205): jxcore cordova android initializing
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 6205): Initializing JXcore engine
W/jxcore-log( 6205): JXcore engine is ready
,W/jxcore-log( 6205): Starting JXcore engine
,W/.test.thalitest( 6205): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10351 path="socket:[5630]" dev="sockfs" ino=5630 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6205): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10351 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6205): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10351 path="socket:[9561]" dev="sockfs" ino=9561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6205): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10351 path="socket:[26949]" dev="sockfs" ino=26949 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6205): Platform android
W/jxcore-log( 6205): 
,W/jxcore-log( 6205): Process ARCH arm
W/jxcore-log( 6205): 
,I/jxcore-log( 6205): JXcore Cordova bridge is ready!
I/jxcore-log( 6205): 
,W/jxcore-log( 6205): JXcore engine is started
I/chromium( 6205): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6205): Toggling radios to true
I/jxcore-log( 6205): 
,D/BluetoothAdapter( 6205): enable(): BT is already enabled..!
,D/WifiService(  887): New client listening to asynchronous messages
,D/WifiService(  887): setWifiEnabled: true pid=6205, uid=10351
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6205): Radios toggled
I/jxcore-log( 6205): 
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/Tethering(  887): InitialState.processMessage what=4
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
V/NativeCrypto( 1645): Read error: ssl=0xb83d94a8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1645): SSL shutdown failed: ssl=0xb83d94a8: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6273 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  887): connected time updated 126329
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  887): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  887): ConnectModeState: Network connection lost 
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6273): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6273): MmsConfig.loadMmsSettings
I/Babel_SMS( 6273): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6273): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6273): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6273): MmsConfig.loadFromResources
,E/Babel_SMS( 6273): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6273): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1428): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  887): [1,449,218,745,559 ms] noteScanEnd no scan source
E/wpa_supplicant( 1428): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@31a66e45 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/Settings( 6273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6273): startup - clean
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 192 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1428): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
,D/Tethering(  887):  5
,D/Tethering(  887):  7
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1428): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2462
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202385488
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/Babel   ( 6273): deleted: false for 0
I/SBar.MotoNetworkCtrlr( 1296): onRecei,ve: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 2
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cbdc843 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cbdc843 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6314 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6314): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6273): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6331): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6331): version 5.5.6 starting
E/DHCPCD  ( 6331): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6331): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6331): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/AudioCapabilities( 6273): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6273): Unsupported mime video/mpeg2
,I/ActivityManager(  887): Killing 5983:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/DHCPCD  ( 6331): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6331): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 6331): wlan0: sending REQUEST (xid 0x8fa23e2f), next in 4.43 seconds
,I/VideoCapabilities( 6273): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6273): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6273): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6273): Unrecognized profile 2130706433 for video/avc
E/global frequency( 2879): no tags to log
D/Checkin ( 2879): publish the event [tag = MOT_CHECKIN event name = LOG]
W/VideoCapabilities( 6273): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  887): failed to open /acct/uid_10057/pid_5983/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 5885:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_5885/cgroup.procs: No such file or directory
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1558): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/vclib   ( 6273): onServiceConnected
W/Babel   ( 6273): Attempted to change video mute state without an active call.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 56619(3MB) AllocSpace objects, 36(1218KB) LOS objects, 40% free, 7MB/12MB, paused 965us total 53.244ms
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2879): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1558): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  887): Explicit concurrent mark sweep GC freed 43973(2MB) AllocSpace objects, 3(225KB) LOS objects, 33% free, 20MB/30MB, paused 1.988ms total 123.434ms
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2879): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1558): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4239(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 736us total 26.879ms
,D/BSUtils ( 2879): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2879): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2879): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2879): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2879): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2879): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2879): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2879): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2879): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2879): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 6331): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 6331): wlan0: leased 192.168.1.134 for 86400 seconds
D/DHCPCD  ( 6331): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 6331): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6331): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6331): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
D/TCMD    (  472): Listening for incoming client connection request
,D/DHCPCD  ( 6331): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ClearcutLoggerApiImpl( 1645): disconnect managed GoogleApiClient
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  887): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887):    accepting network in place of null
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:45:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449218748165], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449218748145]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1540): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1540): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  887): MasterInitialState.processMessage what=3
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6404 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2879): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2879): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2879): [debug] > CusSM.onRadioDown
,V/AlarmManager(  887): send {c8a48b4, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/MusicStore( 6404): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6404): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6205): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): my name is : motorola-XT1072_PT8558
I/jxcore-log( 6205): 
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6404): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6404): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6404): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/jxcore-log( 6205): attempting to connect to test coordinator
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): check test folder
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): found test : ./testFindPeers.js
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): found test : ./testReConnect.js
I/jxcore-log( 6205): 
,W/ActivityThread( 6404): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6404): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6404): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6404): GMSCore installation verified
,I/ConfigStore( 6404): Config Database version: 1
,I/jxcore-log( 6205): found test : ./testSendData.js
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Test app app.js loaded
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/MediaRouter( 6404): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6404): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6404): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6404): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6437 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6404): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6404): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 6021:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6021/cgroup.procs: No such file or directory
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/Mms     ( 6437): mnc/mcc: 
,V/Mms     ( 6437): tag: int value: recipientLimit - 20
,V/Mms     ( 6437): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6437): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6437): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6437): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6437): tag: bool value: enableGroupMms - false
V/Mms     ( 6437):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6463 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5653:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_5653/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6463): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6463): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6463): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 6112:com.google.android.deskclock/u0a55 (adj 15): empty #7
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,W/libprocessgroup(  887): failed to open /acct/uid_10055/pid_6112/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449218627949 min interval config: 0 actual interval: 121409
,I/CheckinService( 1966): Checking schedule, now: 1449218749379 next: 1449218657858
,I/CheckinService( 1966): active receiver: enabled
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1449218623772
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6485 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 68514(3MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 12MB/20MB, paused 912us total 113.449ms
,E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a7532d1)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28088136)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8c1a837)
,E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d3f91a4)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b492b0d)
,I/art     (  887): Explicit concurrent mark sweep GC freed 20651(1013KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.204ms total 119.930ms
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6506 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6273): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6525 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6525): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6525): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6525): VM with version 2.1.0 has multidex support
I/MultiDex( 6525): install
I/MultiDex( 6525): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6525): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6525): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6525): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a292456: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6525): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6525): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6525): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/GAv4    ( 6506): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6506):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6506):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6506): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6506): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6506): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6506): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/NativeLibraryUtils( 6525): Install completed successfully. count=13 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,V/AlarmManager(  887): send {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb10a8960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8ccc4d0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd99c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24cf8, idLength=0xb54b5730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=4249299304
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c46290
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8bf70b8, signature_length=3041613588
,I/WebViewFactory( 6506): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/LibraryLoader( 6506): Time to load native libraries: 3 ms (timestamps 8030-8033)
,I/LibraryLoader( 6506): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6506): Binding Chromium to main looper Looper (main, tid 1) {1ef14f06}
,I/LibraryLoader( 6506): Expected native library version number "",actual native library version number ""
,I/chromium( 6506): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6506): Initializing chromium process, singleProcess=true
W/art     ( 6506): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6506): ApplicationContext is null in ApplicationStatus
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,W/chromium( 6506): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6506): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6506): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6506): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6506): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6506): Local Branch: 
I/Adreno-EGL( 6506): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6506): Local Patches: NONE
I/Adreno-EGL( 6506): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6506): Requires BLUETOOTH permission
,I/NSApplication( 6506): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6593 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6314:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10008/pid_6314/cgroup.procs: No such file or directory
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/Tethering(  887): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 6404): type=WIFI subType= reason=null isConnected=true
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): now: 198337 ,futureTime: 9223372036854775807
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): now: 198338 ,futureTime: 9223372036854775807
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): now: 198338 ,futureTime: 9223372036854775807
D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): now: 198340 ,futureTime: 86473295
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86473295 Current Time: 198341
,D/OtaApp  ( 2879): [debug] > PollingManagerService, now: 198344 ,futureTime: 19138815
D/OtaApp  ( 2879): [debug] > Polling alarm set to expire at: 19138815 Current Time: 198345
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,I/dex2oat ( 6610): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 13656(741KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.003ms total 104.392ms
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2879): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2879): set mOutstandingReq to true.
I/ Nonce  ( 2879):  Nonce getNonce 
I/ Nonce  ( 2879):  Nonce Request 
I/ Nonce  ( 2879):  Nonce execute Request 
,D/MMApiWebService( 2879): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2879): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2879): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2879): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2879): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2879): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiWebService( 2879): generating token using payload instead of using session token
,D/OtaApp  ( 2879): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/ Nonce  ( 2879):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2879): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 6610): dex2oat took 275.942ms (threads: 4)
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6619 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6404:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6525): Local Branch: 
I/Adreno-EGL( 6525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6525): Local Patches: NONE
I/Adreno-EGL( 6525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 26.174ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 353us total 22.089ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.322ms
,I/Adreno-EGL( 6525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6525): Local Branch: 
I/Adreno-EGL( 6525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6525): Local Patches: NONE
I/Adreno-EGL( 6525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6404/cgroup.procs: No such file or directory
,W/ResourcesManager( 6619): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6525): Local Branch: 
I/Adreno-EGL( 6525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6525): Local Patches: NONE
I/Adreno-EGL( 6525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6525): Local Branch: 
I/Adreno-EGL( 6525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6525): Local Patches: NONE
I/Adreno-EGL( 6525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6643 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbeee04e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8bf72f0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd99c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24d18, idLength=0xb10a8730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2183734866
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c41fe0
D/DrmWidevineDash(  295): message_length=1626, signature=0xb8c46928, signature_length=2970257172
I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6666 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6463:com.google.android.setupwizard/u0a35 (adj 13): empty #7
,I/ContactLocale( 6643): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 6437:com.android.mms/u0a23 (adj 15): empty #8
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_6463/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_6437/cgroup.procs: No such file or directory
,I/MusicStore( 6666): Database version: 120
,I/ Nonce  ( 2879):  Nonce Reponse 
D/        ( 2879): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"3a3e79f9-a12c-4a76-88e1-6249fcc5e420"}
D/MMApiWSBase( 2879): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2879):  Nonce Handle Reponse 
D/MMApiProvisionService( 2879): mOutstandingReq set to false
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6666): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4254(182KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.613ms total 32.914ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6666): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6666): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 1966): Sending checkin request (9445 bytes)
,I/art     (  887): Explicit concurrent mark sweep GC freed 12673(630KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 117.846ms
,W/ResourcesManager( 6666): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/MMApiProvisionService( 2879):  pTime 1449056434640 sExp 172742 cTime 1449218752617 tTime 1449229176640
D/MMApiProvisionService( 2879):  No login Required 
,V/JNIHelp ( 6666): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6666): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6666): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6666): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6666): GMSCore installation verified
,I/ConfigStore( 6666): Config Database version: 1
,I/MediaRouter( 6666): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6666): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6666): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6666): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6713 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2879): invalid counter update blocked: 'err' by 0
D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,I/GHttpClientFactory( 6666): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6666): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 6485:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/Mms     ( 6713): mnc/mcc: 
,V/Mms     ( 6713): tag: int value: recipientLimit - 20
,V/Mms     ( 6713): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6713): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6713): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6713): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6713): tag: bool value: enableGroupMms - false
V/Mms     ( 6713):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6485/cgroup.procs: No such file or directory
,W/ResourcesManager( 6713): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6739 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6273:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6273/cgroup.procs: No such file or directory
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/PhoneMonitor( 6739): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6739): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6739): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 6506:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_6506/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449218627949 min interval config: 0 actual interval: 125378
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6767 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1449218753517 next: 1449819890508
,I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checking schedule, now: 1449218753536 next: 1449819890508
,I/CheckinService( 1966): active receiver: disabled
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1449218753539
,I/jxcore-log( 6205): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6205): 
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6792 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6593:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_6593/cgroup.procs: No such file or directory
,W/ResourcesManager( 6792): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Killing 6619:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/Babel_SMS( 6792): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6792): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6792): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6792): MmsConfig.loadFromDatabase
,I/ActivityManager(  887): Killing 6643:android.process.acore/u0a7 (adj 15): empty #8
,E/Babel_SMS( 6792): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6792): MmsConfig.loadFromResources
,E/Babel_SMS( 6792): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6792): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6619/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6643/cgroup.procs: No such file or directory
,W/Settings( 6792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6792): startup - clean
,I/Babel   ( 6792): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6831 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6792): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6792): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6792): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6792): onServiceConnected
W/Babel   ( 6792): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6831): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6831):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6831):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6831): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/Babel   ( 6792): connection state changed from UNKNOWN to CONNECTED
,W/ContextImpl( 6831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  887): Killing 6666:com.google.android.music:main/u0a80 (adj 13): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6831): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6831): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6666/cgroup.procs: No such file or directory
,I/WebViewFactory( 6831): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6831): Time to load native libraries: 2 ms (timestamps 2029-2031)
,I/LibraryLoader( 6831): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6831): Binding Chromium to main looper Looper (main, tid 1) {1ef14f06}
,I/LibraryLoader( 6831): Expected native library version number "",actual native library version number ""
I/chromium( 6831): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6831): Initializing chromium process, singleProcess=true
,W/art     ( 6831): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6831): ApplicationContext is null in ApplicationStatus
,W/chromium( 6831): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6831): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6831): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6831): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6831): Local Branch: 
I/Adreno-EGL( 6831): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6831): Local Patches: NONE
I/Adreno-EGL( 6831): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6831): Requires BLUETOOTH permission
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311833, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-181, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/art     (  887): Explicit concurrent mark sweep GC freed 10779(537KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.671ms total 120.467ms
I/NSApplication( 6831): Starting up...
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6905 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6713:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_6713/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6924 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6739:com.google.android.setupwizard/u0a35 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_6739/cgroup.procs: No such file or directory
,W/ResourcesManager( 6924): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6944 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6792:com.google.android.talk/u0a70 (adj 13): empty #7
,I/ActivityManager(  887): Killing 6767:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 6944): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2879): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6792/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6767/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2879): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2879): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2879): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2879): onServiceConnected()
V/AlarmManager(  887): done {c8a48b4, *walarm*:com.google.android.intent.action.SEND_IDLE} [7320ms]
,D/GetNotificationsWS( 2879): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2879): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6968 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 22.244ms
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/PushService( 2879): started with background data enabled, making sure notification mechanism is enabled
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.684ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 24.897ms
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,E/MDM     ( 1754): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 1966): Restart initialization of location
,D/AuthorizationBluetoothService( 1645): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/AlarmManager(  887): done {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5777ms]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7006 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1754): No location to return for getLastLocation()
,W/FusedLocationProvider( 1645): location=null
,I/MusicStore( 7006): Database version: 120
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 31342(1559KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 11MB/19MB, paused 881us total 61.728ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7006): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7006): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7006): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7006): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7006): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7006): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7006): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7006): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7006): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7006): GMSCore installation verified
,I/ConfigStore( 7006): Config Database version: 1
,I/MediaRouter( 7006): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7006): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7006): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7006): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7042 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7006): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7006): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7042): mnc/mcc: 
,V/Mms     ( 7042): tag: int value: recipientLimit - 20
V/Mms     ( 7042): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7042): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7042): tag: int value: maxSubjectLength - 80
V/Mms     ( 7042): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7042): tag: bool value: enableGroupMms - false
,V/Mms     ( 7042):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7042): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7068 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6831:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7068): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_6831/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7068): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7068): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 6905:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_6905/cgroup.procs: No such file or directory
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449218753539 min interval config: 0 actual interval: 3667
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1966): Checking schedule, now: 1449218757232 next: 1449218783508
I/CheckinService( 1966): active receiver: disabled
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449218753539 min interval config: 0 actual interval: 3718
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7096 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1966): Checking schedule, now: 1449218757341 next: 1449218783508
I/CheckinService( 1966): active receiver: disabled
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7096): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Killing 6924:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6924/cgroup.procs: No such file or directory
,I/Babel_SMS( 7096): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7096): MmsConfig.loadMmsSettings
I/Babel_SMS( 7096): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7096): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7096): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7096): MmsConfig.loadFromResources
,E/Babel_SMS( 7096): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7096): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  887): Explicit concurrent mark sweep GC freed 11771(542KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.476ms total 121.655ms
,W/Settings( 7096): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7096): startup - clean
,I/Babel   ( 7096): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7123 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7096): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7096): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7096): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7096): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7096): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7096): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7096): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7096): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7123): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7123):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7123):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7123): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7096): onServiceConnected
,W/Babel   ( 7096): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7123): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7123): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7123): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7123): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7123): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7123): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7096): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 6944:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6944/cgroup.procs: No such file or directory
,I/WebViewFactory( 7123): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7123): Time to load native libraries: 1 ms (timestamps 5600-5601)
I/LibraryLoader( 7123): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7123): Binding Chromium to main looper Looper (main, tid 1) {1ef14f06}
,I/LibraryLoader( 7123): Expected native library version number "",actual native library version number ""
,I/chromium( 7123): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7123): Initializing chromium process, singleProcess=true
,W/art     ( 7123): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7123): ApplicationContext is null in ApplicationStatus
,W/chromium( 7123): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7123): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7123): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7123): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7123): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7123): Local Branch: 
I/Adreno-EGL( 7123): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7123): Local Patches: NONE
I/Adreno-EGL( 7123): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7123): Starting up...
,W/AudioManagerAndroid( 7123): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7194 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7006:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7006/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7213 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7042:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7042/cgroup.procs: No such file or directory
,W/ResourcesManager( 7213): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7233 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6968:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  887): Killing 7068:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 7233): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2879): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6968/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7068/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2879): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2879): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2879): onServiceConnected()
D/GetNotificationsWS( 2879): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 2879): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 2879): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2879): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2879): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2879): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2879): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2879): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2879): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7266 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2879): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2879): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2879): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2879): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/Keyboard.Facilitator( 1420): onFinishInput()
,W/IInputConnectionWrapper( 6205): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7266): Register our PhoneStateListener
,I/LaunchCheckinHandler(  887): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,193
,V/SetupWizard( 7266): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 6525:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_6525/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7289 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@116c877
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Launcher( 1576): Deferring update until onResume
,V/GmsNetworkLocationProvi( 1754): DISABLE
,I/ActivityManager(  887): Killing 7123:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_7123/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7318 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.930ms
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.968ms
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.407ms
,I/art     (  887): Explicit concurrent mark sweep GC freed 18656(907KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.992ms total 114.287ms
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7355 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7378 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7194:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7194/cgroup.procs: No such file or directory
,W/asset   ( 7378): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7378): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7378): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7378): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7096): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7096): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7096): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7403 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7213:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,W/System  ( 7096): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7096): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7213/cgroup.procs: No such file or directory
,D/Finsky  ( 7403): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7403): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7403): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7403): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7403): Skipping gmscore version check
,D/Finsky  ( 7403): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7403): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7403): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1244c6ff new=com.google.android.velvet.VelvetApplication@1244c6ff
,I/UpdateIcingCorporaServi( 7318): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7403): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7455 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7318): UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
,I/ActivityManager(  887): Killing 7289:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7289/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7266:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7266/cgroup.procs: No such file or directory
,D/TaskPersister(  887): removeObsoleteFile: deleting file=2_task.xml
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  887): done {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ActivityManager(  887): Killing 7355:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7355/cgroup.procs: No such file or directory
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/ActivityManager(  887): Killing 7096:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7096/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310903, SEQNUM=4554, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-213, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1754): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  887): send {35fecd3, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  887): send {28325010, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  887): done {35fecd3, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [17ms]
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1449218753539 min interval config: 0 actual interval: 47296
,I/CheckinService( 1966): Checking schedule, now: 1449218800853 next: 1449218783508
I/CheckinService( 1966): active receiver: enabled
,V/AlarmManager(  887): done {28325010, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [98ms]
,I/CheckinService( 1966): Preparing to send checkin request
I/EventLogService( 1966): Accumulating logs since 1449218749426
,I/CheckinRequestBuilder( 1966): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7519 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,W/ResourcesManager( 7519): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7519): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7519): VM with version 2.1.0 has multidex support
,I/MultiDex( 7519): install
I/MultiDex( 7519): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7519): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7519): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7519): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a292456: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7519): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,E/MDM     ( 1754): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1966): Restart initialization of location
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1645): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/art     ( 7519): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 7519): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1754): No location to return for getLastLocation()
W/FusedLocationProvider( 1645): location=null
,D/NativeLibraryUtils( 7519): Install completed successfully. count=13 extracted=0
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 12960(755KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/19MB, paused 762us total 48.941ms
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb10a8960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8bf70f0, dataLength=8
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bd99c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24cd8, idLength=0xb54b5730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2951186381
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c46290
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8c46ca0, signature_length=3041613588
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7558): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7558): dex2oat took 60.705ms (threads: 4)
,I/Adreno-EGL( 7519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7519): Local Branch: 
I/Adreno-EGL( 7519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7519): Local Patches: NONE
I/Adreno-EGL( 7519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7519): Local Branch: 
I/Adreno-EGL( 7519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7519): Local Patches: NONE
I/Adreno-EGL( 7519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7519): Local Branch: 
I/Adreno-EGL( 7519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7519): Local Patches: NONE
I/Adreno-EGL( 7519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7519): Local Branch: 
I/Adreno-EGL( 7519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7519): Local Patches: NONE
I/Adreno-EGL( 7519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb13cb960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8c59248, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c41fe0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24d18, idLength=0xbeee02b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3415188076
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c41fe0
D/DrmWidevineDash(  295): message_length=1626, signature=0xb8c46928, signature_length=3203269268
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Sending checkin request (9435 bytes)
,I/CheckinRequestBuilder( 1966): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1449218804864 next: 1449819941856
I/CheckinService( 1966): active receiver: disabled
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1449218804881
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7589 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  887): Explicit concurrent mark sweep GC freed 14789(760KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.560ms total 114.731ms
,D/PhoneMonitor( 7589): Register our PhoneStateListener
,V/SetupWizard( 7589): Connected to Gservices successfully
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/ActivityManager(  887): Killing 7318:com.google.android.googlequicksearchbox:search/u0a39 (adj 13): empty #7
,I/ActivityManager(  887): Killing 7378:com.motorola.MotGallery2/u0a27 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7318/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_7378/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7612 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1550ecdb
,V/GmsNetworkLocationProvi( 1754): DISABLE
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7652 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7672 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7403:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_7403/cgroup.procs: No such file or directory
,W/ResourcesManager( 7672): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7672): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7672): MmsConfig.loadMmsSettings
I/Babel_SMS( 7672): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7672): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7672): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7672): MmsConfig.loadFromResources
,E/Babel_SMS( 7672): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7672): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7672): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7672): startup - clean
,I/Babel   ( 7672): deleted: false for 0
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7706 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7672): Unrecognized profile 2130706433 for video/avc
,W/asset   ( 7706): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7706): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7706): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7672): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7672): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7672): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7672): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7672): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7672): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7672): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7728 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.628ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.923ms
,I/ActivityManager(  887): Killing 7455:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 584us total 20.161ms
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7455/cgroup.procs: No such file or directory
,I/vclib   ( 7672): onServiceConnected
,W/Babel   ( 7672): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7672): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7672): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7672): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/Finsky  ( 7728): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System  ( 7672): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7672): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 7728): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7728): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7728): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7728): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7728): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7728): Skipping gmscore version check
,D/Finsky  ( 7728): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1244c6ff new=com.google.android.velvet.VelvetApplication@1244c6ff
,I/UpdateIcingCorporaServi( 7612): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/Finsky  ( 7728): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7776 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7612): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
I/ActivityManager(  887): Killing 7589:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7589/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7519:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_7519/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7652:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7652/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7706:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_7706/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
,I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1645): onCreate
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@163259d5)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a8d55ea)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b5710db)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f971778)
E/DataBuffer( 1645): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b4bbe51)
,I/ConfigService( 1645): onDestroy
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311969, SEQNUM=4576, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-254, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Coordinator is now connected to the server!
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311273, SEQNUM=4580, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-556, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector command called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"38:94:96:B5:06
I/jxcore-log( 6205): Start now : testSendData.js
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): check server
I/jxcore-log( 6205): 
I/jxcore-log( 6205): serverPort is 35822
I/jxcore-log( 6205): 
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 6205): Stoping All
I/        ( 6205): Stopping services
I/        ( 6205): Stop Bluetooth
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 6205): Start-My BT: 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 6205):  mInstanceString : {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}
,I/        ( 6205): All stuff available and enabled
I/        ( 6205): Stoping All
I/        ( 6205): Stopping services
I/        ( 6205): Stop Bluetooth
I/        ( 6205): Starting All
I/        ( 6205): Stopping services
I/        ( 6205): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@286a7353
I/        ( 6205): Stopping services
I/        ( 6205): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}
,I/        ( 6205): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}, length : 81
,D/WifiP2pService(  887): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8556c6c4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8556c6c4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
,D/WifiP2pService(  887): add a new client
,I/        ( 6205): peerDiscoveryTimer timeout value:9173
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Stop Bluetooth
I/        ( 6205): StartBluetooth listener
I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,I/        ( 6205): StartBluetooth listener
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 6205): StartBroadcasting started ok
I/jxcore-log( 6205): 
I/jxcore-log( 6205): do fake peer & start
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:49:52.813Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:49:52.813Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:49:52.813Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/BTListenerThread( 6205): starting to listen
I/BTListenerThread( 6205): waiting to accept incoming Connection
,I/        ( 6205): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 6205): Connecting to null, at 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 2015-12-04T08:49:52.827Z SendDataTCPServer.js: TCP/IP server is bound to port: 35822
I/jxcore-log( 6205): 
I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 6205): Starting to connect
,I/WB      ( 6205): We already were running, thus doing nothing
,I/        ( 6205): Added local service
I/        ( 6205): Cleared service requests
I/        ( 6205): Stopped peer discovery
I/        ( 6205): Started peer discovery
I/        ( 6205): Discovery state changed to Started.
,W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-38
I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
I/wpa_supplicant( 1428): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-57
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 3 peers.
I/SS      ( 6205): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 6205): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 6205): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1428): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
,I/        ( 6205): Started service discovery
,I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 1428): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 f4
,D/MDMCTBK (  293): Event received = P2P-SERV-DISC-REQ 2437 f4
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [38ms]
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
,D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  293): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310778, SEQNUM=4586, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-660, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Cleared service requests
I/        ( 6205): Started peer discovery
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 6 peers.
I/SS      ( 6205): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 6205): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 6205): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 6205): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 6205): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 6205): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 2 c0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1428): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 6205): Started service discovery
,I/wpa_supplicant( 1428): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,W/bt-sdp  ( 2741): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2741): invalid rfc slot id: 5
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 6205): 2015-12-04T08:50:24.660Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:24.660Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:24.661Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1427b05a:true
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
D/MDMCTBK (  293): Event received = P2P-SERV-DISC-REQ 2437 a2
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=7852 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  887): Explicit concurrent mark sweep GC freed 23694(1358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.689ms total 129.842ms
,W/ResourcesManager( 7852): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52d8f68:true
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b52ec67:true
,I/BTConnectionReceiver( 7612): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7612): Bluetooth Device Name: ALE-L21
,I/ActivityManager(  887): Killing 7672:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7672/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 2741): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2741): Entering PendingCommandState State
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=7903 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2741): Removing bonded device:58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
D/BluetoothAdapterService( 2741): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d69d5d
,D/BluetoothMetrics( 2741): btclass5a020c
,D/Checkin ( 2741): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2741): StableState(): Entering Off State
,W/ResourcesManager( 7903): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c8bf0b2:true
,I/ActivityManager(  887): Killing 7728:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_7728/cgroup.procs: No such file or directory
,W/bt-btif ( 2741): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2741): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2741): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 6205): we got incoming connection
I/BTHandshakeSocketThread( 6205): Creating BTHandshakeSocketThread
I/BTListenerThread( 6205): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread started
,I/BTListenerThread( 6205): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 6205): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4512","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 6205): MESSAGE_WRITE 81 bytes.
I/HS      ( 6205): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT4512
I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 6205): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT4512
I/BtToSocketBase( 6205): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6205): Creating BTConnectedThread
,I/BtConnectorHelper( 6205): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 6205): --DoOneRunRound started
,I/BtToRequestSocket( 6205): LocalHost address: localhost/127.0.0.1, port: 35822
,I/BtToRequestSocket( 6205): --DoOneRunRound ended
,I/jxcore-log( 6205): 2015-12-04T08:50:26.817Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.720Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.726Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.732Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.736Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.741Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.763Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.768Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.806Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.813Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.845Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.857Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.862Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.869Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.875Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.905Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.914Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.946Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.962Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:27.996Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.036Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.043Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.047Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.086Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.091Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.126Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.163Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:28.168Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6205): 
,W/bt-btif ( 2741): invalid rfc slot id: 4
,I/BtToSocketBase( 6205): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6205): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 6205): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT4512
I/BtToSocketBase( 6205): Stop ReceivingThread
I/BtToSocketBase( 6205): Stop SendingThread
I/BtToSocketBase( 6205): Close local in
I/BtToSocketBase( 6205): Close LocalOutputStream
I/BtToSocketBase( 6205): Close localHostSocket
I/BtToSocketBase( 6205): Close bt in
I/BtToSocketBase( 6205): Close bt out
I/BtToSocketBase( 6205): Close bt socket
,I/BtToSocketBase( 6205): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 6205): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 6205): 2015-12-04T08:50:28.208Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6205): 
,W/bt-rfcomm( 2741): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2741): RFCOMM_DisconnectInd LCID:0x42
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): 2015-12-04T08:50:29.661Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:29.662Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2 
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 7612): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7612): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 6205): 2015-12-04T08:50:34.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:34.666Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:34.666Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:34.666Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 6205): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2741): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,E/bt-btif ( 2741): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2741): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2741): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2741): StableState(): Entering Off State
,D/BluetoothMetrics( 2741): btclass5a020c
,D/Checkin ( 2741): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2741): new conn_srvc id:26, app_id:1
W/bt-btif ( 2741): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2741): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 6205): Starting to Handshake
,I/BTHandshakeSocketThread( 6205): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 6205): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread started
,I/BTConnectToThread( 6205): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 6205): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 6205): HandshakeOk : LGE-Nexus 5_PT6585
I/HS      ( 6205): Hand Shake finished outgoing for : LGE-Nexus 5_PT6585
I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 6205): Starting the connected thread incoming : false, LGE-Nexus 5_PT6585
,I/BtToSocketBase( 6205): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6205): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 6205): mHTTPPort  set to : 55652
I/BtConnectorHelper( 6205): Request socket is using : 55652
I/BtToRequestSocket( 6205): Now accepting connections
,I/BtConnectorHelper( 6205): Calling ConnectionStatusUpdate with port :55652
I/jxcore-log( 6205): 2015-12-04T08:50:42.598Z SendDataConnector.js: CLIENT connected to 55652, error: null
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:42.598Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6205): 
,I/BtToRequestSocket( 6205): incoming data from: /127.0.0.1, port: 55652
I/BtToRequestSocket( 6205): Set local streams
I/BtToRequestSocket( 6205): rin ended ---------------------------;
,I/jxcore-log( 6205): 2015-12-04T08:50:42.616Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 6205): 2015-12-04T08:50:43.961Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:44.216Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 6205): 2015-12-04T08:50:44.356Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:44.862Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 6205): 2015-12-04T08:50:45.148Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:45.366Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6205): 
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6205): 2015-12-04T08:50:45.433Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:45.666Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:45.844Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6205): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2741): dm_pm_timer expires
W/bt-btif ( 2741): dm_pm_timer expires 0
W/bt-btif ( 2741): proc dm_pm_timer expires
,I/jxcore-log( 6205): 2015-12-04T08:50:55.845Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:55.848Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:50:55.852Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:55.852Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:50:55.853Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 6205): 
,I/BtToSocketBase( 6205): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 6205): Disconnect outgoing peer: LGE-Nexus 5_PT6585
I/BtToSocketBase( 6205): Stop ReceivingThread
I/BtToSocketBase( 6205): Stop SendingThread
I/BtToSocketBase( 6205): Close local in
I/BtToSocketBase( 6205): Close LocalOutputStream
I/BtToSocketBase( 6205): Close localHostSocket
I/BtToSocketBase( 6205): Close bt in
,I/BtToSocketBase( 6205): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 6205): Close bt out
I/BtToSocketBase( 6205): Close bt socket
I/BtToRequestSocket( 6205): Close server socket
,W/bt-btif ( 2741): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6205): 2015-12-04T08:51:00.855Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:00.855Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 7612): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7612): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 6205): 2015-12-04T08:51:05.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:05.858Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:05.858Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:05.859Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 6205): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1428): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1428): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1428): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1428): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1428): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
,D/WifiP2pService(  887): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  887): InitialState.processMessage what=4
,E/WifiStateMachine(  887): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
,E/WifiStateMachine(  887): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
,V/NativeCrypto( 1645): Read error: ssl=0xb850a6d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1645): SSL shutdown failed: ssl=0xb850a6d8: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/jxcore-log( 6205): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): The Coordinator has disconnected!
I/jxcore-log( 6205): 
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7998 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiMetrics(  887): connected time updated 452267
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,D/UdcCache:FPQuery( 1966): Bootstrapping UDC settings cache for all accounts
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1966): CM callback handler got msg 524292
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 7998): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 7998): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7998): MmsConfig.loadMmsSettings
I/Babel_SMS( 7998): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7998): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7998): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7998): MmsConfig.loadFromResources
,E/Babel_SMS( 7998): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7998): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7998): startup - clean
,I/Babel   ( 7998): deleted: false for 0
,W/VideoCapabilities( 7998): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7998): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7998): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7998): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7998): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7998): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7998): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7998): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7998): onServiceConnected
,W/Babel   ( 7998): Attempted to change video mute state without an active call.
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,D/WifiService(  887): setWifiEnabled: false pid=6205, uid=10351
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiScanningService(  887): SCAN_AVAILABLE : 1
D/RttService(  887): SCAN_AVAILABLE : 1
,D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  887): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): [1,449,219,075,182 ms] noteScanEnd no scan source
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
D/WifiP2pService(  887): P2pDisablingState
D/WifiP2pService(  887): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): p2p socket connection lost
D/WifiP2pService(  887): P2pDisabledState
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1428): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): stopping supplicant
,E/WifiStateMachine(  887): setWifiState: disabling
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/wpa_supplicant( 1428): eap_proxy Deinitialzed
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiService(  887): setWifiEnabled: true pid=6205, uid=10351
,E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1428): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293):  Wpa Supplicant Exiting !!
D/MDMCTBK (  293): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  293): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  293): wifi_close_sockets: Exit
,E/WifiStateMachine(  887): Supplicant connection lost
,D/WifiController(  887): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 379ms
W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 6205): Wifi toggled for connection repairment
I/jxcore-log( 6205): 
I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139265 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139265 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Discovery state changed to Stopped.
,I/WB      ( 6205): Wifi is DISABLED !!
I/        ( 6205): Stoping All
I/        ( 6205): Stopping services
,I/        ( 6205): Stopping services
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139298 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139298 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139268 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=0 what=139268 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 6205): Stop Bluetooth
I/        ( 6205): Stop Bluetooth
I/BTListenerThread( 6205): Stopped
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 2741): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:8, channel:-1
I/        ( 6205): Starting peer discovery failed, error code 2
I/        ( 6205): Clearing local services failed, error code 2
I/        ( 6205): Clearing service requests failed, error code 2
I/        ( 6205): Stopping peer discovery failed, error code 2
I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 6205): 2015-12-04T08:51:15.289Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:15.289Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:15.289Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
,E/QC-QMI  (  425): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,E/WifiStateMachine(  887): setWifiState: disabled
,W/Settings( 7998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController(  887): DEFERRED_TOGGLE handled
E/WifiStateMachine(  887): setting operational mode to 1
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{284465fe u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
,D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/QsoftapCmd(  290): Got softap fwreload command we are passing on
,D/SoftapController(  290): Softap fwReload - Ok
,D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring down wlan0
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 8088): Successfully initialized wpa_supplicant
,E/wpa_supplicant( 8088): Line 13: unknown global field '['.
E/wpa_supplicant( 8088): Line 13: Invalid configuration line '['.
,I/wpa_supplicant( 8088): rfkill: Cannot open RFKILL control device
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/libmdmdetect( 8088): ESOC framework not supported
,E/Diag_Lib( 8088):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8088): baseband property is set to [msm]
I/libmdmdetect( 8088): ESOC framework not supported
,E/WifiStateMachine(  887): setWifiState: enabling
,E/WifiStateMachine(  887): Supplicant start successful
D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 8088):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8088): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8088): card_info[i].card_state: 0x0
E/wpa_supplicant( 8088): card_info[i].error_code: 0x0
E/wpa_supplicant( 8088): SIM/USIM not ready
E/wpa_supplicant( 8088): Error while reading SIM card status
,E/wpa_supplicant( 8088): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8088): card_info[i].card_state: 0x0
E/wpa_supplicant( 8088): card_info[i].error_code: 0x0
E/wpa_supplicant( 8088): SIM/USIM not ready
I/wpa_supplicant( 8088): eap_proxy: Card not ready
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8090 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2879): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2879): Registering with Alarm Manager to restart CCE
,E/wpa_supplicant( 8088): Line 31: unknown global field 'r'.
E/wpa_supplicant( 8088): Line 31: Invalid configuration line 'r'.
,I/wpa_supplicant( 8088): rfkill: Cannot open RFKILL control device
D/OtaApp  ( 2879): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2879): [debug] > CusSM.onRadioDown
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/wpa_supplicant( 8088): baseband property is set to [msm]
I/libmdmdetect( 8088): ESOC framework not supported
,E/wpa_supplicant( 8088):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8088): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8088): card_info[i].card_state: 0x0
E/wpa_supplicant( 8088): card_info[i].error_code: 0x0
,E/wpa_supplicant( 8088): SIM/USIM not ready
E/wpa_supplicant( 8088): Error while reading SIM card status
,E/wpa_supplicant( 8088): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8088): card_info[i].card_state: 0x0
E/wpa_supplicant( 8088): card_info[i].error_code: 0x0
E/wpa_supplicant( 8088): SIM/USIM not ready
I/wpa_supplicant( 8088): eap_proxy: Card not ready
,E/WifiStateMachine(  887): setSuspendOptimizations: 2 true
E/WifiStateMachine(  887): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  887): Supplicant connection established
E/WifiStateMachine(  887): setWifiState: enabled
D/WifiConfigStore(  887): Loading config and enabling all networks 
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 7998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  887): Setting external_sim to 1
,D/WifiStateMachine(  887): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e0b89c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb80b6310, mCls = 0x10166a
I/WifiNative-HAL(  887): Could not start hal
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 8088): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  887): do suspend true
,D/WifiScanningService(  887): SCAN_AVAILABLE : 3
,D/RttService(  887): SCAN_AVAILABLE : 3
D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  887): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  887): startHal
,D/CommandListener(  290): Setting iface cfg
I/wpa_supplicant( 8088): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
D/CommandListener(  290): Trying to bring up p2p0
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa492c9cc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb80b6310, mCls = 0x20165e
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
,D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  887): P2pEnablingState
D/WifiP2pService(  887): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
E/WifiStateMachine(  887): set country code US
E/WifiStateMachine(  887): set frequency band 2
,I/wpa_supplicant( 8088): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiP2pService(  887): sending p2p connection changed broadcast
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiNative-HAL(  887): p2pGetDeviceAddress
,D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
I/WB      ( 6205): Wifi is now enabled !
I/        ( 6205): Stoping All
I/        ( 6205): Stopping services
I/        ( 6205): Stop Bluetooth
I/        ( 6205): Starting All
I/        ( 6205): Stopping services
,D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
,I/        ( 6205): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@286a7353
D/WifiP2pService(  887): MCC mode enabled 0
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
I/        ( 6205): Stopping services
,D/WifiP2pService(  887): InactiveState
D/WifiP2pService(  887): InactiveState{ when=-15ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 6205): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}
D/WifiP2pService(  887): P2pEnabledState{ when=-15ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-15ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-15ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8558","ra":"44:80:EB:7B:5A:05"}, length : 81
D/WifiP2pService(  887): InactiveState{ when=0 what=139292 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8556c6c4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139292 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8556c6c4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
I/        ( 6205): peerDiscoveryTimer timeout value:5424
D/WifiP2pService(  887): add a new client
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Stop Bluetooth
D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 6205): StartBluetooth listener
I/        ( 6205): StartBluetooth listener
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  887): discovery change broadcast true
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 6205): Added local service
I/        ( 6205): Cleared service requests
I/        ( 6205): Stopped peer discovery
I/        ( 6205): Discovery state changed to Stopped.
,I/BTListenerThread( 6205): starting to listen
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/BTListenerThread( 6205): waiting to accept incoming Connection
I/        ( 6205): Started peer discovery
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 6205): Discovery state changed to Started.
I/        ( 6205): Started peer discovery
,I/MusicStore( 8090): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 8090): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8090): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8090): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8090): GMSCore installation verified
,I/ConfigStore( 8090): Config Database version: 1
,I/MediaRouter( 8090): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8090): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8130 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8090): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8090): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 7233:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 8130): mnc/mcc: 
V/Mms     ( 8130): tag: int value: recipientLimit - 20
V/Mms     ( 8130): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8130): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8130): tag: int value: maxSubjectLength - 80
V/Mms     ( 8130): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8130): tag: bool value: enableGroupMms - false
V/Mms     ( 8130):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7233/cgroup.procs: No such file or directory
,W/ResourcesManager( 8130): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8161 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7776:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7776/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8161): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8161): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8161): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1966): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1966): num queued entries: 0
I/iu.UploadsManager( 1966): num updated entries: 0
,I/iu.SyncManager( 1966): NEXT; no task
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Killing 7903:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_7903/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8181 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,I/art     (  887): Explicit concurrent mark sweep GC freed 44042(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.513ms total 119.425ms
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8202 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 7998): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 7612:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7612/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8202): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8202): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8202): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8202): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8202): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8202):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8202):   adb logcat -s GAv4
,W/GAv4    ( 8202): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8202): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8202): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8202): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8202): Time to load native libraries: 2 ms (timestamps 6310-6312)
I/LibraryLoader( 8202): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8202): Binding Chromium to main looper Looper (main, tid 1) {38441348}
I/LibraryLoader( 8202): Expected native library version number "",actual native library version number ""
I/chromium( 8202): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8202): Initializing chromium process, singleProcess=true
W/art     ( 8202): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8202): ApplicationContext is null in ApplicationStatus
,W/chromium( 8202): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8202): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8202): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8202): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8202): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8202): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8202): Local Branch: 
I/Adreno-EGL( 8202): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8202): Local Patches: NONE
I/Adreno-EGL( 8202): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8202): Requires BLUETOOTH permission
,I/NSApplication( 8202): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8264 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8090:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8090/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8283 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8130:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 23.994ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.150ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.668ms
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8130/cgroup.procs: No such file or directory
,W/ResourcesManager( 8283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8306 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8325 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8181:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 8306): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/ActivityManager(  887): Killing 8161:com.google.android.setupwizard/u0a35 (adj 15): empty #8
I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8181/cgroup.procs: No such file or directory
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8161/cgroup.procs: No such file or directory
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [81ms]
,I/MusicStore( 8325): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8325): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8325): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8325): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8325): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8325): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8325): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/ActivityThread( 8325): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8325): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8325): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8325): GMSCore installation verified
,I/ConfigStore( 8325): Config Database version: 1
,I/jxcore-log( 6205): 2015-12-04T08:51:20.289Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:20.290Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/MediaRouter( 8325): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8325): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8373 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8325): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8325): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 7998:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 8373): mnc/mcc: 
V/Mms     ( 8373): tag: int value: recipientLimit - 20
,V/Mms     ( 8373): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8373): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8373): tag: int value: maxSubjectLength - 80
V/Mms     ( 8373): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8373): tag: bool value: enableGroupMms - false
,V/Mms     ( 8373):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7998/cgroup.procs: No such file or directory
,W/ResourcesManager( 8373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8407 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8202:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8202/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8407): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8407): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8407): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Killing 8264:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8264/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8428 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8451 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8283:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8283/cgroup.procs: No such file or directory
,W/ResourcesManager( 8451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8451): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8451): MmsConfig.loadMmsSettings
I/Babel_SMS( 8451): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8451): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8451): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8451): MmsConfig.loadFromResources
,E/Babel_SMS( 8451): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8451): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8451): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8451): startup - clean
,I/Babel   ( 8451): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8482 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8451): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8451): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8451): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8451): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8451): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8451): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8451): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8451): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8451): onServiceConnected
W/Babel   ( 8451): Attempted to change video mute state without an active call.
,I/Babel   ( 8451): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 8306:android.process.acore/u0a7 (adj 15): empty #7
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8306/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8482): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/WifiStateMachine(  887): [1,449,219,081,823 ms] noteScanEnd no scan source
,I/GAv4    ( 8482): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8482):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8482):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8482): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8482): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 8482): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8482): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8482): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8482): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  887): Explicit concurrent mark sweep GC freed 15108(788KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.452ms total 116.306ms
,I/WebViewFactory( 8482): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8482): Time to load native libraries: 2 ms (timestamps 9501-9503)
,I/LibraryLoader( 8482): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8482): Binding Chromium to main looper Looper (main, tid 1) {38441348}
I/LibraryLoader( 8482): Expected native library version number "",actual native library version number ""
,I/chromium( 8482): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8482): Initializing chromium process, singleProcess=true
,W/art     ( 8482): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8482): ApplicationContext is null in ApplicationStatus
,W/chromium( 8482): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8482): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8482): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8482): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8482): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8482): Local Branch: 
I/Adreno-EGL( 8482): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8482): Local Patches: NONE
I/Adreno-EGL( 8482): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8482): Requires BLUETOOTH permission
,I/NSApplication( 8482): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8550 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8325:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8325/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8569 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8373:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8373/cgroup.procs: No such file or directory
,W/ResourcesManager( 8569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8589 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8428:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  887): Killing 8407:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 8589): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2879): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8428/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8407/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2879): bindWebServices(): registering our AIDL callback...
I/SundryService( 2879): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2879): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2879): onServiceConnected()
D/GetNotificationsWS( 2879): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2879): unbindWebServices(): un-registering our AIDL callback...
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8622 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.007ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.385ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.975ms
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  887): done {3f2c9804, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [3470ms]
,I/ActivityManager(  887): Killing 8482:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8482/cgroup.procs: No such file or directory
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 2 peers.
I/SS      ( 6205): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 6205): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 8088): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 6205): Started service discovery
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6205): 2015-12-04T08:51:25.300Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:25.300Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:25.300Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:25.300Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 6205): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:2, scn:-145887048
,W/bt-btif ( 2741): invalid rfc slot id: 10
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6205): 2015-12-04T08:51:25.329Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:25.329Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:25.330Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6205): 2015-12-04T08:51:30.338Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:30.339Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-44
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 6205): 2015-12-04T08:51:35.354Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:35.354Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.355Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.355Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/        ( 6205): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:2, scn:-145887048
,W/bt-btif ( 2741): invalid rfc slot id: 11
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6205): 2015-12-04T08:51:35.386Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:35.386Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:35.393Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.393Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.394Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): ---- round done--------
I/jxcore-log( 6205): 
I/jxcore-log( 6205): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 6205): 
I/jxcore-log( 6205): do fake peer & start
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.398Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.398Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.398Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 6205): Connecting to null, at 34:FC:EF:11:AE:67
I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:2, scn:-145887048
,W/bt-btif ( 2741): invalid rfc slot id: 12
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6205): 2015-12-04T08:51:35.416Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:35.417Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:35.418Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311462, SEQNUM=4690, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-19030, POWER_SUPPLY_CHARGE_COUNTER=-854, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 6205): 2015-12-04T08:51:40.426Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:40.426Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
,I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6205): 2015-12-04T08:51:45.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:45.438Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:45.438Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:45.438Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 6205): Connecting to null, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 6205): Starting to connect
,W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:2, scn:-145887048
,W/bt-btif ( 2741): invalid rfc slot id: 13
,I/BTConnectToThread( 6205): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 6205): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 6205): 2015-12-04T08:51:45.468Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:45.469Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:45.470Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Cleared service requests
,I/        ( 6205): Started peer discovery
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6205): 2015-12-04T08:51:50.479Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:50.480Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 5 peers.
,I/SS      ( 6205): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 6205): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 6205): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 6205): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 6205): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-57
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2741): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
,E/bt-btif ( 2741): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2741): invalid rfc slot id: 8
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 6205): Started service discovery
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-41
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2124","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2124, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2124, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5092","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5092, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5092, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 6205): 2015-12-04T08:51:55.490Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:55.491Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:55.491Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:55.491Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
,I/        ( 6205): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 6205): Connecting to null, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 6205): Starting to connect
W/BluetoothAdapter( 6205): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2741): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312323, SEQNUM=4698, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-901, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2741): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2741): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2741): Entering PendingCommandState State
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8678 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 1966:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  887): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1c139961)
,D/WifiService(  887): Client connection lost with reason: 4
,I/BluetoothBondStateMachine( 2741): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2741): Failed to remove device: 34:FC:EF:11:AE:67
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_1966/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2741): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,D/BluetoothMetrics( 2741): btclass5a020c
,W/ResourcesManager( 8678): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/BluetoothBondStateMachine( 2741): StableState(): Entering Off State
D/ConnectivityService(  887): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  887): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Checkin ( 2741): publish the event [tag = MOT_BT event name = PAIRING]
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@338c5947:true
,I/ActivityManager(  887): Killing 8550:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8550/cgroup.procs: No such file or directory
,W/bt-btif ( 2741): new conn_srvc id:26, app_id:1
W/bt-btif ( 2741): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2741): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 6205): Starting to Handshake
I/BTHandshakeSocketThread( 6205): Creating BTHandshakeSocketThread
I/BTConnectToThread( 6205): MESSAGE_WRITE 81 bytes.
I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread started
,I/BTConnectToThread( 6205): got MESSAGE_READ 75 bytes.
I/BTConnectToThread( 6205): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT74","ra":"34:FC:EF:11:AE:67"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 6205): HandshakeOk : LGE-Nexus 5_PT74
I/HS      ( 6205): Hand Shake finished outgoing for : LGE-Nexus 5_PT74
,I/BtConnectorHelper( 6205): Starting the connected thread incoming : false, LGE-Nexus 5_PT74
I/BtToSocketBase( 6205): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 6205): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 6205): BTHandshakeSocketThread fully stopped
I/BtToRequestSocket( 6205): mHTTPPort  set to : 46753
I/BtConnectorHelper( 6205): Request socket is using : 46753
I/BtToRequestSocket( 6205): Now accepting connections
,I/BtConnectorHelper( 6205): Calling ConnectionStatusUpdate with port :46753
,I/jxcore-log( 6205): 2015-12-04T08:51:57.287Z SendDataConnector.js: CLIENT connected to 46753, error: null
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:51:57.287Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6205): 
,I/BtToRequestSocket( 6205): incoming data from: /127.0.0.1, port: 46753
I/BtToRequestSocket( 6205): Set local streams
I/BtToRequestSocket( 6205): rin ended ---------------------------;
,I/jxcore-log( 6205): 2015-12-04T08:51:57.311Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 6205): 2015-12-04T08:51:58.227Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:58.377Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 6205): 2015-12-04T08:51:58.671Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:51:58.970Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6205): 
,D/        ( 2741): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 6205): 2015-12-04T08:51:59.230Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6205): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6205): 2015-12-04T08:51:59.601Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6205): 2015-12-04T08:52:00.224Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:00.301Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6205): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Cleared service requests
,I/        ( 6205): Started peer discovery
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-46
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService(  887):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService(  887):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 8 peers.
I/SS      ( 6205): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 6205): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 6205): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 6205): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 6205): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 6205): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 6205): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 6205): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 8088): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 6205): Started service discovery
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-11ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-11ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-16ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-16ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7300","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7300, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7300, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1124","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1124, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1124, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2741): dm_pm_timer expires
,W/bt-btif ( 2741): dm_pm_timer expires 0
W/bt-btif ( 2741): proc dm_pm_timer expires
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 6205): Cleared service requests
,I/        ( 6205): Started peer discovery
,I/jxcore-log( 6205): 2015-12-04T08:52:10.301Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:10.301Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:52:10.302Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:52:10.302Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6205): 
I/jxcore-log( 6205): 2015-12-04T08:52:10.302Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 6205): 
,I/BtToSocketBase( 6205): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 6205): Disconnect outgoing peer: LGE-Nexus 5_PT74
I/BtToSocketBase( 6205): Stop ReceivingThread
I/BtToSocketBase( 6205): Stop SendingThread
I/BtToSocketBase( 6205): Close local in
I/BtToSocketBase( 6205): Close LocalOutputStream
I/BtToSocketBase( 6205): Close localHostSocket
I/BtToSocketBase( 6205): Close bt in
,I/BtToSocketBase( 6205): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 6205): Close bt out
,I/BtToSocketBase( 6205): Close bt socket
I/BtToRequestSocket( 6205): Close server socket
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-45
D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 11 peers.
I/SS      ( 6205): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 6205): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 6205): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 6205): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 6205): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 6205): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 6205): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 6205): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 6205): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 6205): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 6205): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=45 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,W/bt-btif ( 2741): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 6205): Started service discovery
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-6ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT4869"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT4869, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT4869, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4244","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4244, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4244, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5230","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT5230, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT5230, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5039"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5039, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5039, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6585"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT6585, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT6585, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT8320"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT8320, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT8320, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8263","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT8263, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT8263, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5358"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5358, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5358, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/ConnectivityService(  887): Failed to find a new network - expiring NetTransition Wakelock
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 6205): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"}, typeCordovap2p._tcp.local.:
,I/        ( 6205): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT3722"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT3722, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 6205): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT3722, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Cleared service requests
,I/        ( 6205): Started peer discovery
,I/jxcore-log( 6205): 2015-12-04T08:52:15.310Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:15.311Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8736 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cab42e3:true
,I/BTConnectionReceiver( 8736): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8771 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8736): Bluetooth Device Name: Nexus 5
,I/ActivityManager(  887): Killing 8569:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8569/cgroup.procs: No such file or directory
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-44
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-48
D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 8088): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 8088): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 6205): Cleared service requests
,I/        ( 6205): Started peer discovery
,I/wpa_supplicant( 8088): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 6205): Found 12 peers.
I/SS      ( 6205): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 6205): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 6205): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 6205): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 6205): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 6205): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 6205): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 6205): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 6205): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 6205): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 6205): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 6205): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=52 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6205): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 6205): Added service request
,I/jxcore-log( 6205): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6205): 
I/jxcore-log( 6205): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6205): 
,D/WifiService(  887): setWifiEnabled: false pid=6205, uid=10351
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/wpa_supplicant( 8088): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 8088): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiScanningService(  887): SCAN_AVAILABLE : 1
D/RttService(  887): SCAN_AVAILABLE : 1
,D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  887): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): [1,449,219,140,233 ms] noteScanEnd no scan source
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): discovery change broadcast false
,D/WifiP2pService(  887): P2pDisablingState
D/WifiP2pService(  887): P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): p2p socket connection lost
D/WifiP2pService(  887): P2pDisabledState
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): stopping supplicant
,E/WifiStateMachine(  887): setWifiState: disabling
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiService(  887): setWifiEnabled: true pid=6205, uid=10351
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,I/wpa_supplicant( 8088): eap_proxy Deinitialzed
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiController(  887): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 399ms
I/wpa_supplicant( 8088): wlan0: CTRL-EVENT-TERMINATING 
E/WifiStateMachine(  887): Supplicant connection lost
,I/jxcore-log( 6205): Wifi toggled for connection repairment
I/jxcore-log( 6205): 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/chromium( 6205): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139265 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=0 what=139265 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 6205): Discovery state changed to Stopped.
I/WB      ( 6205): Wifi is DISABLED !!
,I/        ( 6205): Stoping All
I/        ( 6205): Stopping services
I/        ( 6205): Stopping services
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139298 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139298 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 6205): Stop Bluetooth
I/        ( 6205): Stop Bluetooth
I/BTListenerThread( 6205): Stopped
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139268 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139268 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6205): 2015-12-04T08:52:20.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:20.320Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:20.320Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6205): 
,I/jxcore-log( 6205): 2015-12-04T08:52:20.320Z SendDataConnector.js: do connect now
I/jxcore-log( 6205): 
D/AndroidRuntime( 6205): Shutting down VM
,E/QC-QMI  (  425): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/WifiStateMachine(  887): setWifiState: disabled
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 22
E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 24
E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 23
,E/QC-QMI  (  425): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 25
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/Settings( 8451): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController(  887): DEFERRED_TOGGLE handled
E/WifiStateMachine(  887): setting operational mode to 1
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,D/Checkin ( 3311): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
,D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
,D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/QsoftapCmd(  290): Got softap fwreload command we are passing on
D/SoftapController(  290): Softap fwReload - Ok
,D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring down wlan0
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  887): setWifiState: enabling
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): Supplicant start successful
,D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 8853): Successfully initialized wpa_supplicant
,E/wpa_supplicant( 8853): Line 13: unknown global field 'N'.
,E/wpa_supplicant( 8853): Line 13: Invalid configuration line 'N'.
I/wpa_supplicant( 8853): rfkill: Cannot open RFKILL control device
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/libmdmdetect( 8853): ESOC framework not supported
,E/Diag_Lib( 8853):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8853): baseband property is set to [msm]
I/libmdmdetect( 8853): ESOC framework not supported
,E/wpa_supplicant( 8853):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): card_info[i].card_state: 0x0
E/wpa_supplicant( 8853): card_info[i].error_code: 0x0
E/wpa_supplicant( 8853): SIM/USIM not ready
E/wpa_supplicant( 8853): Error while reading SIM card status
,E/wpa_supplicant( 8853): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): card_info[i].card_state: 0x0
E/wpa_supplicant( 8853): card_info[i].error_code: 0x0
E/wpa_supplicant( 8853): SIM/USIM not ready
I/wpa_supplicant( 8853): eap_proxy: Card not ready
,E/wpa_supplicant( 8853): Line 31: unknown global field 'rr'.
,E/wpa_supplicant( 8853): Line 31: Invalid configuration line 'rr'.
,I/wpa_supplicant( 8853): rfkill: Cannot open RFKILL control device
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/wpa_supplicant( 8853): baseband property is set to [msm]
,I/libmdmdetect( 8853): ESOC framework not supported
,E/wpa_supplicant( 8853):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): card_info[i].card_state: 0x0
E/wpa_supplicant( 8853): card_info[i].error_code: 0x0
E/wpa_supplicant( 8853): SIM/USIM not ready
E/wpa_supplicant( 8853): Error while reading SIM card status
,E/wpa_supplicant( 8853): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8853): card_info[i].card_state: 0x0
E/wpa_supplicant( 8853): card_info[i].error_code: 0x0
E/wpa_supplicant( 8853): SIM/USIM not ready
I/wpa_supplicant( 8853): eap_proxy: Card not ready
,E/WifiStateMachine(  887): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  887): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  887): Supplicant connection established
,E/WifiStateMachine(  887): setWifiState: enabled
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  887): Loading config and enabling all networks 
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 8451): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  887): Setting external_sim to 1
,D/WifiStateMachine(  887): Setting OUI to DA-A1-19
I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e0b89c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb80b6310, mCls = 0x1015da
,I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 8853): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring up p2p0
,D/WifiScanningService(  887): SCAN_AVAILABLE : 3
D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  887): startHal
D/RttService(  887): SCAN_AVAILABLE : 3
D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  887): P2pEnablingState
,D/WifiP2pService(  887): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
D/RttService(  887): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): sending p2p connection changed broadcast
,E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa492c9cc
,D/wifi    (  887): halHandle = 0x0, mVM = 0xb80b6310, mCls = 0x10157a
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
I/wpa_supplicant( 8853): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/WifiNative-HAL(  887): p2pGetDeviceAddress
,D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
E/WifiStateMachine(  887): set country code US
,D/WifiP2pService(  887): MCC mode enabled 0
,D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
E/WifiStateMachine(  887): set frequency band 2
,I/wpa_supplicant( 8853): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
D/WifiP2pService(  887): InactiveState
,D/WifiP2pService(  887): InactiveState{ when=-6ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-6ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-7ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  887): [1,449,219,145,518 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@31a66e45 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  887): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  887):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,I/wpa_supplicant( 8853): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 8853): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiConfigStore(  887): setLastSelectedConfiguration -1
,E/wpa_supplicant( 8853): PNO: In assoc process
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 192 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8853): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/TCMD    (  472): NL - Read 80 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 8853): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 8853): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 3
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 8853): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 8853): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@716f9c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@716f9c target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,E/DHCPCD  ( 8895): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 8895): version 5.5.6 starting
,E/DHCPCD  ( 8895): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 8895): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 8895): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 8895): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 8895): wlan0: rebinding lease of 192.168.1.134
,D/DHCPCD  ( 8895): wlan0: sending REQUEST (xid 0xe26db84e), next in 4.84 seconds
,I/DHCPCD  ( 8895): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 8895): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DHCPCD  ( 8895): wlan0: adding IP address 192.168.1.134/24
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
D/TCMD    (  472): Listening for incoming client connection request
,D/DHCPCD  ( 8895): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 8895): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 8895): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 8895): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 102
E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  887): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887):    accepting network in place of null
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:52:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449219148012], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449219147987]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1540): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1540): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524295
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{330f6a9d u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2879): now: 598089 ,futureTime: 9223372036854775807
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): now: 598090 ,futureTime: 9223372036854775807
D/PollingManager( 2879): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2879): now: 598090 ,futureTime: 9223372036854775807
D/OtaApp  ( 2879): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8966 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Central_PollingManager( 1465): now: 598146 ,futureTime: 86473295
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86473295 Current Time: 598146
D/OtaApp  ( 2879): [debug] > PollingManagerService, now: 598147 ,futureTime: 19138815
D/OtaApp  ( 2879): [debug] > Polling alarm set to expire at: 19138815 Current Time: 598147
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2879): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2879): set mOutstandingReq to true.
I/ Nonce  ( 2879):  Nonce getNonce 
I/ Nonce  ( 2879):  Nonce Request 
I/ Nonce  ( 2879):  Nonce execute Request 
,D/MMApiWebService( 2879): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  887): Explicit concurrent mark sweep GC freed 67245(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.394ms total 126.492ms
,D/MMApiProvisionService( 2879): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore( 8966): Database version: 120
,D/CCE     ( 2879): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2879): createDeviceIdOrLogin update_device
D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2879): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2879): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2879): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2879): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2879): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2879): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2879): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2879): generating token using payload instead of using session token
,D/ Nonce  ( 2879):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2879): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8966): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8966): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8966): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 8966): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8966): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dad0189: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8966): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8966): GMSCore installation verified
,I/ConfigStore( 8966): Config Database version: 1
,I/MediaRouter( 8966): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8966): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 8966): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 8966): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9017 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8966): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8966): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9043 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/Mms     ( 9017): mnc/mcc: 
,V/Mms     ( 9017): tag: int value: recipientLimit - 20
,V/Mms     ( 9017): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9017): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9017): tag: int value: maxSubjectLength - 80
V/Mms     ( 9017): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9017): tag: bool value: enableGroupMms - false
,V/Mms     ( 9017):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  887): Killing 8589:android.process.acore/u0a7 (adj 15): empty #7
,W/ResourcesManager( 9043): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9043): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 9043): VM with version 2.1.0 has multidex support
I/MultiDex( 9043): install
I/MultiDex( 9043): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8589/cgroup.procs: No such file or directory
,W/ResourcesManager( 9017): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9070 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8622:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8622/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9070): Register our PhoneStateListener
,V/JNIHelp ( 9043): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/ Nonce  ( 2879):  Nonce Reponse 
D/        ( 2879): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7282b012-2135-49c7-bb9d-7d89dedfd343"}
D/MMApiWSBase( 2879): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2879):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2879): mOutstandingReq set to false
,D/MobileConnectivityChangeReceiver( 9070): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9070): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 8451:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 7446(380KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 953us total 29.419ms
,W/ActivityThread( 9043): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9043): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9a9f58c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9043): Installed default security provider GmsCore_OpenSSL
,D/MMApiProvisionService( 2879):  pTime 1449056434640 sExp 172742 cTime 1449219152135 tTime 1449229176640
D/MMApiProvisionService( 2879):  No login Required 
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8451/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 9043): Install completed successfully. count=13 extracted=0
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 7058(414KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 11MB/15MB, paused 737us total 45.723ms
,I/CheckinService( 9043): Checkin interval check for package: unspecified last checkin: 1449218804881 min interval config: 0 actual interval: 347416
,I/CheckinService( 9043): Disabling old GoogleServicesFramework version
,I/CheckinService( 9043): Checking schedule, now: 1449219152352 next: 1449218834856
I/CheckinService( 9043): active receiver: enabled
,I/CheckinService( 9043): Preparing to send checkin request
,I/EventLogService( 9043): Accumulating logs since 1449218800931
,I/iu.SyncManager( 9043): SYNC; picasa accounts
,D/NetworkLogImpl( 9043): Loaded NetworkSpeedPredictor
,I/iu.Environment( 9043): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/art     ( 9043): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 9043): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/iu.UploadsManager( 9043): num queued entries: 0
,I/iu.UploadsManager( 9043): num updated entries: 0
,I/iu.SyncManager( 9043): NEXT; no task
,D/ChimeraCfgMgr( 9043): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 9043): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/DataUsage( 2879): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2879): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9118 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 9043): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9043): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  887): Explicit concurrent mark sweep GC freed 13130(658KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.748ms total 136.691ms
D/WifiService(  887): New client listening to asynchronous messages
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9146 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8678:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_8678/cgroup.procs: No such file or directory
,W/ResourcesManager( 9146): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9163 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 9163): VM with version 2.1.0 has multidex support
I/MultiDex( 9163): install
I/MultiDex( 9163): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 9163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/Babel_SMS( 9146): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9146): MmsConfig.loadMmsSettings
I/Babel_SMS( 9146): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9146): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9146): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9146): MmsConfig.loadFromResources
,E/Babel_SMS( 9146): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9146): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 9163): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a292456: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9163): Installed default security provider GmsCore_OpenSSL
,W/Settings( 9146): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 9146): startup - clean
,I/art     ( 9163): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 9163): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/Babel   ( 9146): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9194 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 9163): Install completed successfully. count=13 extracted=0
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.152ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 19.160ms
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.198ms
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
W/VideoCapabilities( 9146): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55b5960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8bf7200, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c41fe0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24cf8, idLength=0xb13cb730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=828096979
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c46290
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8c46a78, signature_length=2973546260
W/AudioCapabilities( 9146): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 9146): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9146): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 9146): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9146): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9146): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9146): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9146): onServiceConnected
W/Babel   ( 9146): Attempted to change video mute state without an active call.
,I/Babel   ( 9146): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 8736:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/GAv4    ( 9194): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9194):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9194):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9194): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9194): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/art     ( 9146): Suspending all threads took: 7.464ms
W/ContextImpl( 9194): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9194): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_8736/cgroup.procs: No such file or directory
,W/GAv4    ( 9194): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9194): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9194): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9194): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 9238): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LibraryLoader( 9194): Time to load native libraries: 2 ms (timestamps 1306-1308)
I/LibraryLoader( 9194): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9194): Binding Chromium to main looper Looper (main, tid 1) {1ef14f06}
I/LibraryLoader( 9194): Expected native library version number "",actual native library version number ""
I/chromium( 9194): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9194): Initializing chromium process, singleProcess=true
W/art     ( 9194): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9194): ApplicationContext is null in ApplicationStatus
,I/dex2oat ( 9238): dex2oat took 57.656ms (threads: 4)
,W/chromium( 9194): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9194): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9194): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9194): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9194): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9194): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9194): Local Branch: 
I/Adreno-EGL( 9194): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9194): Local Patches: NONE
I/Adreno-EGL( 9194): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9163): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9163): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9163): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9163): Local Branch: 
I/Adreno-EGL( 9163): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9163): Local Patches: NONE
I/Adreno-EGL( 9163): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9194): Requires BLUETOOTH permission
,I/NSApplication( 9194): Starting up...
,I/Adreno-EGL( 9163): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9163): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9163): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9163): Local Branch: 
I/Adreno-EGL( 9163): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9163): Local Patches: NONE
I/Adreno-EGL( 9163): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9263 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8771:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/Adreno-EGL( 9163): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9163): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9163): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9163): Local Branch: 
I/Adreno-EGL( 9163): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9163): Local Patches: NONE
I/Adreno-EGL( 9163): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9163): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9163): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9163): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9163): Local Branch: 
I/Adreno-EGL( 9163): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9163): Local Patches: NONE
I/Adreno-EGL( 9163): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_8771/cgroup.procs: No such file or directory
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fda000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9290 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/ActivityManager(  887): Killing 8966:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54b5960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8cca4f0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c41fe0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8d24d18, idLength=0xb10a8730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2168434610
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c41fe0
D/DrmWidevineDash(  295): message_length=1626, signature=0xb8bd9208, signature_length=2970257172
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8966/cgroup.procs: No such file or directory
,W/ResourcesManager( 9290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9320 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 9043): Classify the device as Phone.
,I/ActivityManager(  887): Killing 9070:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 9320): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 9017:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_9070/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2879): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_9017/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2879): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2879): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2879): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2879): onServiceConnected()
D/GetNotificationsWS( 2879): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2879): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2879): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2879): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2879): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2879): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2879): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2879): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,E/MDM     ( 1754): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 32020(1871KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 11MB/19MB, paused 1.104ms total 75.003ms
D/OtaApp  ( 2879): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2879): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2879): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2879): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2879): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2879): publish the event [tag = MOT_OTA event name = LOG]
,W/InstanceID/Rpc( 9043): Found 10016
,D/LocationInitializer( 9043): Restart initialization of location
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1645): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 9043): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1754): [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 1645): Explicit concurrent mark sweep GC freed 7325(446KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 11MB/15MB, paused 671us total 56.837ms
,I/CheckinTask( 9043): Sending checkin request (9431 bytes)
,W/GCoreFlp( 1754): No location to return for getLastLocation()
,W/FusedLocationProvider( 1645): location=null
,D/LocationInitializer( 9043): Restart initialization of location
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1645): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 9043): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1754): No location to return for getLastLocation()
W/FusedLocationProvider( 1645): location=null
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=291, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311617, SEQNUM=4804, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-986, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/CheckinRequestBuilder( 9043): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9043): Failed to find provider info for com.google.android.wearable.settings
,W/SQLiteConnectionPool( 9043): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinRequestBuilder( 9043): Classify the device as Phone.
,I/CheckinTask( 9043): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9043): Checking schedule, now: 1449219156774 next: 1449820293766
I/CheckinService( 9043): active receiver: disabled
,D/CheckinService( 9043): Recording last checkin time for package unspecified as 1449219156784
,I/art     (  887): Explicit concurrent mark sweep GC freed 13880(671KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.556ms total 117.316ms
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9391 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9391): Register our PhoneStateListener
,V/SetupWizard( 9391): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 9194:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_9194/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 9043): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 9043): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1645): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  887): Killing 9263:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_9263/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 9290:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_9290/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9415 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2dca8115
,V/GmsNetworkLocationProvi( 1754): DISABLE
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9452 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9473 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 9146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 9473): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9473): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9473): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,V/JNIHelp ( 9146): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9497 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 9146): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9146): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Killing 9118:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_9118/cgroup.procs: No such file or directory
,D/Finsky  ( 9497): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 9497): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9497): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9497): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 9497): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 9497): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 9497): Skipping gmscore version check
,D/Finsky  ( 9497): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/UpdateIcingCorporaServi( 9415): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1244c6ff new=com.google.android.velvet.VelvetApplication@1244c6ff
,D/PackageBroadcastService( 9043): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9548 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 9043): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 9497): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 9548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 9043): Storage manager: low false usage 1.69MB avail 2.69GB capacity 4.12GB
,I/UpdateIcingCorporaServi( 9415): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
,I/ActivityManager(  887): Killing 9391:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/Icing   ( 9043): Received bad json for section weights override -- ignoring.
,W/Icing   ( 9043): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 9043): Received bad json for section weights override -- ignoring.
W/Icing   ( 9043): Received bad json for corpus context scoring override -- ignoring.
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_9391/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 9163:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/Icing   ( 9043): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_9163/cgroup.procs: No such file or directory
,I/Icing   ( 9043): Internal init done: storage state 0
,I/Icing   ( 9043): Post-init done
,I/Icing   ( 9043): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  887): Killing 9452:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_9452/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 9146:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_9146/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 9043): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
,I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311986, SEQNUM=4819, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-1022, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
,I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311852, SEQNUM=4821, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-1120, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
,I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {15d6af1c, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  887): done {15d6af1c, *walarm*:android.content.syncmanager.SYNC_ALARM} [7ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50b7e65:true
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:ae:67]: 6, f, 6109
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/art     (  887): Explicit concurrent mark sweep GC freed 19747(994KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.600ms total 126.528ms
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:b1:66]: 7, f, 6109
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:ae:67]: 6, f, 6109
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {25708f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,V/AlarmManager(  887): done {25708f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [26ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [44ms]
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [34:fc:ef:11:b1:66]: 7, f, 6109
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {d85c73a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  887): cleanup(): cleared. Last call was 437650 ms ago
I/ActivityManager(  887): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=9688 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [104ms]
,I/GAv4    ( 9688): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9688):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9688):   adb logcat -s GAv4
,W/GAv4    ( 9688): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9688): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9688): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  887): done {d85c73a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [263ms]
I/ActivityManager(  887): Killing 9473:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_9473/cgroup.procs: No such file or directory
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2741): tBTM_SEC_DEV:0xa6f4dddc rs_disc_pending=1
,W/bt-btif ( 2741): bta_dm_check_av:0
,W/bt-btif ( 2741): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2741): tBTM_SEC_DEV:0xa6f4df9c rs_disc_pending=0
,W/bt-btif ( 2741): bta_dm_check_av:0
W/bt-btif ( 2741): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ActivityManager(  887): Killing 9497:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_9497/cgroup.procs: No such file or directory
,E/bt-btm  ( 2741): tBTM_SEC_DEV:0xa6f4d35c rs_disc_pending=0
W/bt-btif ( 2741): bta_dm_check_av:0
,W/bt-btif ( 2741): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2741): tBTM_SEC_DEV:0xa6f4df9c rs_disc_pending=1
,W/bt-btif ( 2741): bta_dm_check_av:0
W/bt-btif ( 2741): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2741): tBTM_SEC_DEV:0xa6f4d35c rs_disc_pending=0
,W/bt-btif ( 2741): bta_dm_check_av:0
,W/bt-btif ( 2741): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311792, SEQNUM=4847, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2120, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/bt-btif ( 2741): info:x10
D/        ( 2741): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2741): onReceive
,I/BTConnectionReceiver( 9415): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9415): Bluetooth Device Name: A5-1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{300d5fc7 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  887): User[0] Flushing usage stats to disk
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2741): info:x10
,D/        ( 2741): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2741): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2741): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2741): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311152, SEQNUM=4849, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=8683, POWER_SUPPLY_CHARGE_COUNTER=163, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311109, SEQNUM=4851, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311407, SEQNUM=4853, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {25708f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  887): send {23ca99f4, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  887): done {25708f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [18ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  887): done {23ca99f4, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [52ms]
,I/EventLogService( 9043): Aggregate from 1449219152697 (log), 1449218001385 (data)
,I/art     (  887): Explicit concurrent mark sweep GC freed 15752(888KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/30MB, paused 1.551ms total 120.307ms
,D/UdcCache:FPQuery( 9043): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4-SVC( 9043): Google Analytics 8.3.01 is starting up.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311373, SEQNUM=4856, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-171, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311066, SEQNUM=4857, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-201, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {6353507, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  887): send {14113f51, *walarm*:com.google.android.apps.plus.checkandengagesync}
,V/AlarmManager(  887): send {1648d3b6, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  887): Prepared write state in 24ms
,V/AlarmManager(  887): done {6353507, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [62ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [80ms]
,V/AlarmManager(  887): done {14113f51, *walarm*:com.google.android.apps.plus.checkandengagesync} [102ms]
,V/AlarmManager(  887): done {1648d3b6, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [109ms]
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1645): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  887): Pruning old procstats: /data/system/procstats/state-2015-12-03-07-21-11.bin
,I/art     ( 1754): Explicit concurrent mark sweep GC freed 33852(1746KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 11MB/18MB, paused 1.343ms total 80.266ms
,E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@156fd21b)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {15d6af1c, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  887): done {15d6af1c, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {2b92c33d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {1e2157b5, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  887): done {1e2157b5, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [17ms]
,V/AlarmManager(  887): done {2b92c33d, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311650, SEQNUM=4862, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2741): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 9796): 
D/AndroidRuntime( 9796): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9796): CheckJNI is OFF
D/AndroidRuntime( 9796): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10351 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 6205:com.test.thalitest/u0a351 (adj 9): stop com.test.thalitest
W/PackageSettings(  887): Skipping PackageSetting{77c404a com.example.hello/10343} due to missing metadata
I/WindowState(  887): WIN DEATH: Window{1345a18e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  887): Client connection lost with reason: 4
I/ActivityManager(  887):   Force finishing activity ActivityRecord{24c935eb u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  887): Spurious death for ProcessRecord{7e9ae4a 6205:com.test.thalitest/u0a351}, curProc for 6205: null
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10351 user=0: pkg removed
I/art     ( 3311): Explicit concurrent mark sweep GC freed 23522(3MB) AllocSpace objects, 39(624KB) LOS objects, 39% free, 7MB/12MB, paused 773us total 51.592ms
I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1754): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 9320): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
I/Decoder ( 1420): createOrResetDecoder
I/art     ( 1576): Explicit concurrent mark sweep GC freed 5104(314KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 518us total 138.094ms
I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9827 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.371ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 19.447ms
I/art     (  887): Explicit concurrent mark sweep GC freed 22593(1405KB) AllocSpace objects, 8(209KB) LOS objects, 33% free, 20MB/30MB, paused 1.848ms total 173.317ms
I/art     (  887): WaitForGcToComplete blocked for 113.558ms for cause Explicit
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.501ms
I/ConfigService( 1645): onCreate
W/asset   ( 9827): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9827): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9827): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9827): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1645): Classify the device as Phone.
I/ActivityManager(  887): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=9850 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  887): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  887): removeObsoleteFile: deleting file=3_task.xml
I/art     (  887): Explicit concurrent mark sweep GC freed 5895(298KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.583ms total 190.891ms
I/Launcher( 1576): Deferring update until onResume
W/ContextImpl( 9850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9870 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 9415:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 9796): Shutting down VM
W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_9415/cgroup.procs: No such file or directory
D/Finsky  ( 9870): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 9870): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 9870): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 9870): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Ads     ( 9870): Skipping gmscore version check
I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=9917 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  887): Killing 9043:com.google.android.gms/u0a16 (adj 15): empty #7
D/WifiService(  887): Client connection lost with reason: 4
W/ActivityManager(  887): Application dead when creating service ServiceRecord{1068f89d u0 com.google.android.gms/.ads.identifier.service.AdvertisingIdService}
W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_9043/cgroup.procs: No such file or directory
W/ActivityManager(  887): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
W/ActivityManager(  887): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 4000ms
W/ActivityManager(  887): Spurious death for ProcessRecord{35f316f4 0:com.google.android.gms/u0a16}, curProc for 9043: null
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
