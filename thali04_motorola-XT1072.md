#### Test 550731521dbc378_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
D/AndroidRuntime( 6312): 
D/AndroidRuntime( 6312): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6312): CheckJNI is OFF
D/AndroidRuntime( 6312): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6332 uid=10410 gids={50410, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6312): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6332): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6332): Time to load native libraries: 2 ms (timestamps 7438-7440)
,I/LibraryLoader( 6332): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6332): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 6332): Expected native library version number "",actual native library version number ""
,I/chromium( 6332): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6332): Initializing chromium process, singleProcess=true
W/art     ( 6332): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6332): ApplicationContext is null in ApplicationStatus
,W/chromium( 6332): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6332): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6332): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6332): Local Branch: 
I/Adreno-EGL( 6332): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6332): Local Patches: NONE
I/Adreno-EGL( 6332): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
,D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@253db6dd:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{2551d0ee u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6332): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6332): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6332): CordovaWebView is running on device made by: motorola
,W/art     ( 6332): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6332): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6332): Render dirty regions requested: true
,D/Atlas   ( 6332): Validating map...
,W/chromium( 6332): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6332): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6332): Enabling debug mode 0
,I/Keyboard.Facilitator( 1423): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,993
,I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +918ms (total +993ms)
,W/IInputConnectionWrapper( 6332): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6332): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6332): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6332): Cannot call determinedVisibility() - never saw a connection for the pid: 6332
,D/JsMessageQueue( 6332): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6332): JniHelper::setJavaVM(0xb77a4310), pthread_self() = -1212987328
D/JX-Cordova( 6332): jxcore cordova android initializing
,W/jxcore-log( 6332): Initializing JXcore engine
W/jxcore-log( 6332): JXcore engine is ready
,W/jxcore-log( 6332): Starting JXcore engine
,W/.test.thalitest( 6332): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10410 path="socket:[5784]" dev="sockfs" ino=5784 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6332): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10410 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6332): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10410 path="socket:[7631]" dev="sockfs" ino=7631 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6332): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10410 path="socket:[29445]" dev="sockfs" ino=29445 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6332): Platform android
W/jxcore-log( 6332): 
,W/jxcore-log( 6332): Process ARCH arm
W/jxcore-log( 6332): 
,I/jxcore-log( 6332): JXcore Cordova bridge is ready!
I/jxcore-log( 6332): 
,W/jxcore-log( 6332): JXcore engine is started
I/chromium( 6332): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6332): Toggling radios to true
I/jxcore-log( 6332): 
,D/BluetoothAdapter( 6332): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,D/WifiService(  885): setWifiEnabled: true pid=6332, uid=10410
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6332): Radios toggled
I/jxcore-log( 6332): 
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6332): Received device characteristics:
I/jxcore-log( 6332): Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6332): Bluetooth name: XT1072
I/jxcore-log( 6332): Device name: motorola-XT1072
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): Perf Test app loaded loaded
I/jxcore-log( 6332): 
I/jxcore-log( 6332): check test folder
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): found test : ./testFindPeers.js
I/jxcore-log( 6332): 
,I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291):  STA Disconnected !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  508): NL - Read 1004 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 68 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 68 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  885): InitialState.processMessage what=4
I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 6332): found test : ./testSendData.js
I/jxcore-log( 6332): 
E/wpa_supplicant( 1395): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  508): NL - Read 60 bytes from update socket.
D/TCMD    (  508): NL - ignore NL message, type = 21
D/TCMD    (  508): Listening for incoming client connection request
V/NativeCrypto( 1721): Read error: ssl=0xb7af5600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1721): SSL shutdown failed: ssl=0xb7af5600: I/O error during system call, Broken pipe
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/WifiMetrics(  885): connected time updated 294219
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6399 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/ModemStatsDSDetect( 1539): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1539): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1539): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1539): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1539): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1539): onReceive() - done, currentInetCondition=0
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1395): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1395): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/CommandListener(  289): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/chromium( 6332): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6399): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6423 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6073:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6073/cgroup.procs: No such file or directory
,W/ResourcesManager( 6423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  291): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  885): [1,451,989,393,852 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1395): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1395): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  291): Event received = Trying to associate with
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6423): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6423): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6423): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6423): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6423): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6423): MmsConfig.loadFromResources
,E/Babel_SMS( 6423): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6423): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6423): startup - clean
,I/Babel   ( 6423): deleted: false for 0
,D/TCMD    (  508): NL - Read 312 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 192 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 68 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 1004 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
I/wpa_supplicant( 1395): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  508): NL - Read 80 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 80 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/TCMD    (  508): NL - Read 68 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  291): Event received = Associated with c0:ff:d4
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
,E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
,D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1395): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  291): Event received = WPA: Key negotiation com
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291):  STA Connected !!
,D/TCMD    (  508): NL - Read 1004 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
E/MDMCTBK (  291): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  291): get_freq !!, resp=2412
I/MDMCTBK (  291): get_freq !!, Strip data
I/MDMCTBK (  291): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  291): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  291): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197256456
I/MDMCTBK (  291): return from set_get_from_wpa_supplicant
E/WifiStateMachine(  885): Network connection established
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  291): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  291): , reply_len: 3, ret: 0
E/MDMCTBK (  291): MdmCutbackHndler, resp=OK
E/MDMCTBK (  291): 
D/MDMCTBK (  291): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1395): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1395): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@386b851e target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@386b851e target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6423): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6423): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6423): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6105:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/DHCPCD  ( 6463): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6463): version 5.5.6 starting
,E/DHCPCD  ( 6463): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6463): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6463): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6105/cgroup.procs: No such file or directory
,I/vclib   ( 6423): onServiceConnected
,W/Babel   ( 6423): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6463): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6463): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6463): wlan0: sending REQUEST (xid 0x78646f4c), next in 4.34 seconds
,I/DHCPCD  ( 6463): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6463): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6463): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6463): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6463): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6463): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  508): NL - Read 60 bytes from update socket.
D/TCMD    (  508): NL - ignore NL message, type = 20
D/TCMD    (  508): Listening for incoming client connection request
,D/DHCPCD  ( 6463): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1539): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1539): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1539): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 10:23:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451989396199], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451989396169]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1539): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1539): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1539): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1539): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6541 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1481): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2550): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2550): [debug] > CusSM.onRadioDown
,I/jxcore-log( 6332): Connected to the server!
I/jxcore-log( 6332): 
,I/chromium( 6332): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MusicStore( 6541): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6541): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6541): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6541): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  885): Explicit concurrent mark sweep GC freed 51951(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.542ms total 154.916ms
,W/ResourcesManager( 6541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/JNIHelp ( 6541): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,W/ActivityThread( 6541): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6541): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6541): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6541): GMSCore installation verified
,I/ConfigStore( 6541): Config Database version: 1
,I/MediaRouter( 6541): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6541): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6541): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6541): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6596 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6541): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6541): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 5931:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5931/cgroup.procs: No such file or directory
,V/Mms     ( 6596): mnc/mcc: 
,V/Mms     ( 6596): tag: int value: recipientLimit - 20
V/Mms     ( 6596): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6596): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6596): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6596): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6596): tag: bool value: enableGroupMms - false
,V/Mms     ( 6596):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6596): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6628 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6013:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6628): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6013/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6628): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6628): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6423:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6423/cgroup.procs: No such file or directory
,I/CheckinService( 6161): Checkin interval check for package: unspecified last checkin: 1451989143603 min interval config: 0 actual interval: 254114
,I/CheckinService( 6161): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6161): SYNC; picasa accounts
,I/CheckinService( 6161): Checking schedule, now: 1451989397752 next: 1451989173584
I/CheckinService( 6161): active receiver: enabled
,D/NetworkLogImpl( 6161): Loaded NetworkSpeedPredictor
,I/CheckinService( 6161): Preparing to send checkin request
,I/iu.Environment( 6161): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6161): Accumulating logs since 1451989139503
,I/iu.UploadsManager( 6161): num queued entries: 0
,I/iu.UploadsManager( 6161): num updated entries: 0
,I/iu.SyncManager( 6161): NEXT; no task
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6656 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6161): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
,E/ActivityThread( 6161): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6678 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6695 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6678): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6332): BLE is supported
I/jxcore-log( 6332): 
,I/MultiDex( 6678): VM with version 2.1.0 has multidex support
,I/MultiDex( 6678): install
I/MultiDex( 6678): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6678): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6678): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6678): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6678): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6678): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6678): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6695): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6695): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6695): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6695): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6695): MmsConfig.loadFromResources
,E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6695): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6695): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NativeLibraryUtils( 6678): Install completed successfully. count=14 extracted=0
,I/Babel_Crash( 6695): startup - clean
,I/Babel   ( 6695): deleted: false for 0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb501d000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb501d000
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6731 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54f8960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8cba3a0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d50418, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,I/art     (  317): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 27.048ms
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8daaa78, idLength=0xbec042b0
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 19.719ms
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3660207020
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c94d00
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8cb2c20, signature_length=3200270996
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.768ms
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6695): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6695): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6695): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6695): onServiceConnected
W/Babel   ( 6695): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 6695): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 6399:com.motorola.context/u0a8 (adj 15): empty #7
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/dex2oat ( 6754): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6399/cgroup.procs: No such file or directory
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): now: 369331 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1481): now: 369340 ,futureTime: 86473431
D/Central_PollingManager( 1481): Polling alarm set to expire at: 86473431 Current Time: 369341
I/NetworkMonitor( 6541): type=WIFI subType= reason=null isConnected=true
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 369341 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 369342 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2550): [debug] > PollingManagerService, now: 369346 ,futureTime: 21234581
,D/OtaApp  ( 2550): [debug] > Polling alarm set to expire at: 21234581 Current Time: 369346
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,I/dex2oat ( 6754): dex2oat took 89.132ms (threads: 4)
D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Adreno-EGL( 6678): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6678): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6678): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6678): Local Branch: 
I/Adreno-EGL( 6678): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6678): Local Patches: NONE
I/Adreno-EGL( 6678): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6678): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6678): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6678): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6678): Local Branch: 
I/Adreno-EGL( 6678): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6678): Local Patches: NONE
I/Adreno-EGL( 6678): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  885): Explicit concurrent mark sweep GC freed 14071(671KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.944ms total 124.411ms
D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2550): set mOutstandingReq to true.
I/ Nonce  ( 2550):  Nonce getNonce 
I/ Nonce  ( 2550):  Nonce Request 
I/ Nonce  ( 2550):  Nonce execute Request 
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2550): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2550): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/art     ( 1481): Explicit concurrent mark sweep GC freed 4420(196KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.123ms total 45.495ms
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/ContextImpl( 6731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6731): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/MMApiWebService( 2550): generating token using payload instead of using session token
,I/GAv4    ( 6731): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6731):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6731):   adb logcat -s GAv4
,D/ Nonce  ( 2550):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2550): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,W/GAv4    ( 6731): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb501d000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb501d000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54f8960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8c8a000, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c7d7e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8daaab8, idLength=0xb55f8730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=456818732
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c94d00
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8cba488, signature_length=3042936596
W/GAv4    ( 6731): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6731): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6731): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6731): Time to load native libraries: 1 ms (timestamps 9976-9977)
,I/LibraryLoader( 6731): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6731): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 6731): Expected native library version number "",actual native library version number ""
,I/chromium( 6731): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6731): Initializing chromium process, singleProcess=true
,W/art     ( 6731): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6731): ApplicationContext is null in ApplicationStatus
,W/chromium( 6731): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6731): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6731): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6731): Local Branch: 
I/Adreno-EGL( 6731): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6731): Local Patches: NONE
I/Adreno-EGL( 6731): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6731): Requires BLUETOOTH permission
,I/NSApplication( 6731): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6807 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6541:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6678): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6678): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6678): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6678): Local Branch: 
I/Adreno-EGL( 6678): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6678): Local Patches: NONE
I/Adreno-EGL( 6678): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6678): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6678): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6678): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6678): Local Branch: 
I/Adreno-EGL( 6678): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6678): Local Patches: NONE
I/Adreno-EGL( 6678): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6541/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6826 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6596:com.android.mms/u0a23 (adj 15): empty #7
,I/CheckinRequestBuilder( 6161): Classify the device as Phone.
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6596/cgroup.procs: No such file or directory
,W/ResourcesManager( 6826): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6853 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinTask( 6161): Sending checkin request (9520 bytes)
,I/ Nonce  ( 2550):  Nonce Reponse 
D/        ( 2550): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"5bca6122-6c4e-4d44-8de3-2d51b1fc5028"}
D/MMApiWSBase( 2550): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2550):  Nonce Handle Reponse 
D/MMApiProvisionService( 2550): mOutstandingReq set to false
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6874 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6656:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/MMApiProvisionService( 2550):  pTime 1451923699777 sExp 172742 cTime 1451989400848 tTime 1452096441777
D/MMApiProvisionService( 2550):  No login Required 
,I/ContactLocale( 6853): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 6628:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/CheckinRequestBuilder( 6161): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6656/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6628/cgroup.procs: No such file or directory
,E/ActivityThread( 6161): Failed to find provider info for com.google.android.wearable.settings
,W/DataUsage( 2550): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 6874): Database version: 120
,I/art     ( 6133): Explicit concurrent mark sweep GC freed 1535(66KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 367us total 33.084ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6874): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6161): Classify the device as Phone.
,I/CheckinTask( 6161): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6161): Checking schedule, now: 1451989401321 next: 1452590538315
I/CheckinService( 6161): active receiver: disabled
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6874): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
D/CheckinService( 6161): Recording last checkin time for package unspecified as 1451989401334
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6874): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files,
,I/ActivityManager(  885): Killing 6695:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6695/cgroup.procs: No such file or directory
,W/ResourcesManager( 6874): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6874): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6874): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6874): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6874): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6874): GMSCore installation verified
,I/ConfigStore( 6874): Config Database version: 1
,I/art     (  885): Explicit concurrent mark sweep GC freed 8853(467KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.500ms total 118.145ms
,I/MediaRouter( 6874): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6874): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6874): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Killing 6731:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_6731/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6874): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6932 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6874): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6874): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6807:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_6807/cgroup.procs: No such file or directory
,V/Mms     ( 6932): mnc/mcc: 
V/Mms     ( 6932): tag: int value: recipientLimit - 20
,V/Mms     ( 6932): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6932): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6932): tag: int value: maxSubjectLength - 80
V/Mms     ( 6932): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6932): tag: bool value: enableGroupMms - false
V/Mms     ( 6932):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6932): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6961 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6826:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6826/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6961): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6961): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6961): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6853:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6853/cgroup.procs: No such file or directory
,I/CheckinService( 6161): Checkin interval check for package: unspecified last checkin: 1451989401334 min interval config: 0 actual interval: 951
,I/CheckinService( 6161): Checking schedule, now: 1451989402302 next: 1451989431315
,I/CheckinService( 6161): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6983 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  885): send {dd4578d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {337d7120, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  885): send {3a11ad9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {dd4578d, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7003 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6874:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6874/cgroup.procs: No such file or directory
,W/ResourcesManager( 7003): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7003): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7003): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7003): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7003): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7003): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7003): MmsConfig.loadFromResources
,E/Babel_SMS( 7003): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7003): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7003): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7003): startup - clean
,I/Babel   ( 7003): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7030 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7003): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7003): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7003): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7003): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7003): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7003): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7003): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7003): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7003): onServiceConnected
,W/Babel   ( 7003): Attempted to change video mute state without an active call.
,I/GAv4    ( 7030): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7030):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7030):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7030): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7030): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7030): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7030): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7030): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7030): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7030): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7003): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 6932:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6932/cgroup.procs: No such file or directory
,I/WebViewFactory( 7030): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7030): Time to load native libraries: 1 ms (timestamps 3958-3959)
I/LibraryLoader( 7030): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7030): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7030): Expected native library version number "",actual native library version number ""
I/chromium( 7030): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7030): Initializing chromium process, singleProcess=true
,W/art     ( 7030): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7030): ApplicationContext is null in ApplicationStatus
,W/chromium( 7030): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7030): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7030): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7030): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7030): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7030): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7030): Local Branch: 
I/Adreno-EGL( 7030): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7030): Local Patches: NONE
I/Adreno-EGL( 7030): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7030): Requires BLUETOOTH permission
,I/NSApplication( 7030): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7105 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6961:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6961/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7124 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6983:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/art     (  317): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.471ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 339us total 20.773ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 21.688ms
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6983/cgroup.procs: No such file or directory
,W/ResourcesManager( 7124): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7144 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7030:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7144): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7003:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7030/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7003/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
,D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7173 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2550): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1721): callingUid 10016, callindPid: 1721
,E/MDM     ( 1721): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1721): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6161): Restart initialization of location
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7204 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1721): No location to return for getLastLocation()
,W/FusedLocationProvider( 1721): location=null
,I/MusicStore( 7204): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7204): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  885): Explicit concurrent mark sweep GC freed 11922(565KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.567ms total 132.939ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7204): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7204): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7204): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7204): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7204): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7204): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7204): GMSCore installation verified
,I/ConfigStore( 7204): Config Database version: 1
,I/MediaRouter( 7204): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7204): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7204): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7204): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7239 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7204): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7204): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7105:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7239): mnc/mcc: 
,V/Mms     ( 7239): tag: int value: recipientLimit - 20
V/Mms     ( 7239): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7239): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7239): tag: int value: maxSubjectLength - 80
V/Mms     ( 7239): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7239): tag: bool value: enableGroupMms - false
,V/Mms     ( 7239):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7105/cgroup.procs: No such file or directory
,W/ResourcesManager( 7239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7265 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7124:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7265): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7124/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7265): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7265): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7144:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7144/cgroup.procs: No such file or directory
,I/CheckinService( 6161): Checkin interval check for package: unspecified last checkin: 1451989401334 min interval config: 0 actual interval: 4826
,I/CheckinService( 6161): Checkin interval check for package: unspecified last checkin: 1451989401334 min interval config: 0 actual interval: 4827
,I/CheckinService( 6161): Checking schedule, now: 1451989406169 next: 1451989431315
,I/CheckinService( 6161): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7285 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6161): Checking schedule, now: 1451989406230 next: 1451989431315
I/CheckinService( 6161): active receiver: disabled
,W/ResourcesManager( 7285): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/Babel_SMS( 7285): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7285): MmsConfig.loadMmsSettings
I/Babel_SMS( 7285): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7285): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7285): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7285): MmsConfig.loadFromResources
,E/Babel_SMS( 7285): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7285): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7285): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7285): startup - clean
,I/Babel   ( 7285): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7316 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7285): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7285): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7285): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7285): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7285): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7285): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7285): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7285): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7285): onServiceConnected
,W/Babel   ( 7285): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7316): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7316): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7316): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7316):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7316):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7316): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7316): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7316): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7285): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 6678:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/GAv4    ( 7316): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7316): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6678/cgroup.procs: No such file or directory
,I/WebViewFactory( 7316): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7316): Time to load native libraries: 2 ms (timestamps 7358-7360)
,I/LibraryLoader( 7316): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7316): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7316): Expected native library version number "",actual native library version number ""
,I/chromium( 7316): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7316): Initializing chromium process, singleProcess=true
,W/art     ( 7316): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7316): ApplicationContext is null in ApplicationStatus
,W/chromium( 7316): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7316): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7316): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7316): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7316): Local Branch: 
I/Adreno-EGL( 7316): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7316): Local Patches: NONE
I/Adreno-EGL( 7316): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7316): Requires BLUETOOTH permission
,I/NSApplication( 7316): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7387 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7204:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7204/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7406 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7239:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7239/cgroup.procs: No such file or directory
,W/ResourcesManager( 7406): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7426 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 7173:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ContactLocale( 7426): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7265:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7173/cgroup.procs: No such file or directory
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7265/cgroup.procs: No such file or directory
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@768eb05
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/GCoreNlp( 1721): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2550): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2550): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2550): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2550): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,I/Launcher( 1568): Deferring update until onResume
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1423): onFinishInput()
,W/IInputConnectionWrapper( 6332): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,141
,I/art     (  885): Explicit concurrent mark sweep GC freed 18318(925KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.071ms total 152.804ms
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7464 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.040ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 23.485ms
,D/PhoneMonitor( 7464): Register our PhoneStateListener
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.807ms
,V/SetupWizard( 7464): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 7285:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7285/cgroup.procs: No such file or directory
,V/AlarmManager(  885): done {337d7120, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6144ms]
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7488 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  885): done {3a11ad9, *walarm*:android.content.syncmanager.SYNC_ALARM} [6184ms]
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7514 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7316:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7316/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7544 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7561 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7387:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7406:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7387/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7406/cgroup.procs: No such file or directory
,W/ResourcesManager( 7561): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7561): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7561): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7561): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7561): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7561): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7561): MmsConfig.loadFromResources
,E/Babel_SMS( 7561): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7561): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7561): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7561): startup - clean
,I/Babel   ( 7561): deleted: false for 0
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7594 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7561): Unrecognized profile 2130706433 for video/avc
,W/asset   ( 7594): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7594): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7594): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7594): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7561): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7561): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7561): Unsupported profile 4 for video/mp4v-es
,D/PackageBroadcastService( 6161): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/VideoCapabilities( 7561): Unrecognized profile 2130706433 for video/avc
I/UpdateIcingCorporaServi( 7514): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/VideoCapabilities( 7561): Unrecognized profile 2130706433 for video/avc
,I/PackageBroadcastService( 6161): Null package name or gms related package.  Ignoreing.
W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,W/VideoCapabilities( 7561): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7561): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7622 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6161): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7622): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7561): onServiceConnected
W/Babel   ( 7561): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7561): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7561): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7514): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
,I/ActivityManager(  885): Killing 7488:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7561): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7561): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7561): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7488/cgroup.procs: No such file or directory
,I/art     ( 1721): Explicit concurrent mark sweep GC freed 105376(5MB) AllocSpace objects, 30(503KB) LOS objects, 40% free, 15MB/25MB, paused 1.040ms total 108.154ms
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d496a42)
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27ae8a53)
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22a85f90)
E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@82ec089)
E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d87e88e)
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1220f7c1)
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23cc7b66)
,E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@228dcea7)
E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27820f54)
E/DataBuffer( 1721): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22044efd)
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7660 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7464:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7464/cgroup.procs: No such file or directory
,D/Finsky  ( 7660): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7660): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7660): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7660): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7660): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7660): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7660): Skipping gmscore version check
D/Finsky  ( 7660): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7660): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 7544:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_7544/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6161): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6161): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6161): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 7594:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_7594/cgroup.procs: No such file or directory
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310294, SEQNUM=4474, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-766, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ActivityManager(  885): Killing 7514:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_7514/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/CheckinService( 6161): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=245, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310642, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-852, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1423): run()
I/Keyboard.Facilitator( 1423): flushDynamicLanguageModels()
,I/ConfigService( 1721): onCreate
,I/ConfigService( 1721): onDestroy
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6332): --- start :testFindPeers.js---
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): testFindPeers created [object Object]
I/jxcore-log( 6332): 
I/jxcore-log( 6332): serverPort is 8876
I/jxcore-log( 6332): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): bind: Binding a new listener
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6332): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6332): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): start: OK
I/io.jxcore.node.ConnectionHelper( 6332): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6332): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6332): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  885): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service
,D/WifiP2pService(  885): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): start: Starting P2P device discovery...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6332): start: OK
,I/jxcore-log( 6332): StartBroadcasting started ok
I/jxcore-log( 6332): 
,I/chromium( 6332): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6332): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6332): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  885): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 39,2
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-81
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-4ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6332): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): weAreDoneNow
I/jxcore-log( 6332): 
I/jxcore-log( 6332): done, now sending data to server
I/jxcore-log( 6332): 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: RESTARTING
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): P2P-FIND-STOPPED 
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  885): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast false
,D/WifiP2pService(  885): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  885): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): Start timer timeout, starting now...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139265 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139265 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 a2
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 0a
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  885):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3-1
D/WifiP2pService(  885):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 ee
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 ee
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=56 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=56 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 2 
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-81
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6332): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=62 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=62 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
,D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-5ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-5ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  508): NL - Read 56 bytes from update socket.,
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,I/jxcore-log( 6332): teardown
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): testFindPeers stopped
I/jxcore-log( 6332): 
,I/io.jxcore.node.ConnectionHelper( 6332): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): stop: Stopping services
D/WifiP2pService(  885): InactiveState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139298 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6332): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setState: NOT_STARTED
,I/jxcore-log( 6332): StopBroadcasting went ok
I/jxcore-log( 6332): 
,I/chromium( 6332): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6332): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6332): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6332): --- start :testSendData.js---
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 0
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): daya100000
I/jxcore-log( 6332): 
I/jxcore-log( 6332): check server
I/jxcore-log( 6332): 
I/jxcore-log( 6332): serverPort is 33327
I/jxcore-log( 6332): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): bind: Binding a new listener
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): P2P-FIND-STOPPED 
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  885): InactiveState{ when=-9ms what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-9ms what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
D/WifiP2pService(  885): remove channel information from framework
D/WifiP2pService(  885): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast false
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2,pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6332): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6332): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): start: OK
I/io.jxcore.node.ConnectionHelper( 6332): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6332): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6332): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  885): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service
D/WifiP2pService(  885): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): start: Starting P2P device discovery...
D/WifiP2pService(  885): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6332): start: OK
I/jxcore-log( 6332): StartBroadcasting started ok
I/jxcore-log( 6332): 
I/jxcore-log( 6332): null
I/jxcore-log( 6332): 
I/jxcore-log( 6332): 2016-01-05T10:26:49.236Z SendDataTCPServer.js: TCP/IP server is bound to port: 33327
I/jxcore-log( 6332): 
I/chromium( 6332): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6332): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): Waiting for incoming connections...
D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): P2P-FIND-STOPPED 
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  885): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6332): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: RESTARTING
D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-81
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6332): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6332): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): Start timer timeout, starting now...
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=139265 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139265 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
,D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-25
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
,D/TCMD    (  508): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 7e
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=25 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=25 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6332): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service request added successfully
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  508): NL - Read 56 bytes from update socket.
,D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service discovery started successfully
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 a2
,I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
I/wpa_supplicant( 1395): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 a2
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2437 a2
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/TCMD    (  508): NL - Read 56 bytes from update socket.
D/TCMD    (  508): NL - message type is RTM_NEWLINK
D/TCMD    (  508): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 6332): teardown
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): testSendData stopped
I/jxcore-log( 6332): 
,I/io.jxcore.node.ConnectionHelper( 6332): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6332): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6332): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6332): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6332): stop: Stopping services
,D/WifiP2pService(  885): InactiveState{ when=0 what=139298 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139298 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): stop: Stopping P2P device discovery...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1395): P2P-FIND-STOPPED 
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1395): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  885): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast false
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.St,ateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): setState: NOT_INITIALIZED
,D/WifiP2pService(  885): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
D/WifiP2pService(  885): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6332): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6332): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6332): setState: NOT_STARTED
I/jxcore-log( 6332): StopBroadcasting went ok
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): 2016-01-05T10:27:06.143Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6332): 
,I/jxcore-log( 6332): 2016-01-05T10:27:06.147Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6332): 
I/chromium( 6332): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6332): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6332): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6332): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6332): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6332): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6332): ****TEST TOOK:  ms ****
I/jxcore-log( 6332): 
I/jxcore-log( 6332): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6332): 
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,D/AndroidRuntime( 7757): 
D/AndroidRuntime( 7757): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7757): CheckJNI is OFF
,D/AndroidRuntime( 7757): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10410 user=-1: uninstall pkg
,I/ActivityManager(  885): Killing 6332:com.test.thalitest/u0a410 (adj 9): stop com.test.thalitest
,W/PackageSettings(  885): Skipping PackageSetting{f36067b com.example.hello/10406} due to missing metadata
,I/WindowState(  885): WIN DEATH: Window{fbf114d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  885): Client connection lost with reason: 4
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{2551d0ee u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  885): Spurious death for ProcessRecord{1a4d8588 6332:com.test.thalitest/u0a410}, curProc for 6332: null
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10410 user=0: pkg removed
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{2551d0ee u0 com.test.thalitest/.MainActivity t3 f}
,W/ActivityManager(  885): Duplicate finish request for ActivityRecord{2551d0ee u0 com.test.thalitest/.MainActivity t3 f}
,I/art     ( 2992): Explicit concurrent mark sweep GC freed 10094(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 7MB/12MB, paused 761us total 53.507ms
,I/Keyboard.Facilitator( 1423): resetDictionaries() : en_US
,I/art     ( 1568): Explicit concurrent mark sweep GC freed 4656(291KB) AllocSpace objects, 5(240KB) LOS objects, 24% free, 13MB/17MB, paused 482us total 46.712ms
,W/GeofencerStateMachine( 1721): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1423): run()
,I/Decoder ( 1423): createOrResetDecoder
,D/VoicemailCleanupService( 7426): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7788 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 48766(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.818ms total 159.949ms
,I/art     (  885): WaitForGcToComplete blocked for 97.812ms for cause Explicit
,I/ConfigService( 1721): onCreate
,W/asset   ( 7788): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7788): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7788): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7788): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1423): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1423): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1423): run()
I/StatsUtilsManager( 1423): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1423): shouldRecordStats() = Too Soon
,I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7813 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  885): removeObsoleteFile: deleting file=3_task.xml
,I/art     (  885): Explicit concurrent mark sweep GC freed 10095(579KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.494ms total 192.629ms
,I/Launcher( 1568): Deferring update until onResume
I/ActivityManager(  885): Killing 7622:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7622/cgroup.procs: No such file or directory
,D/AndroidRuntime( 7757): Shutting down VM
,W/ContextImpl( 7813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6161): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6161): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6161): Reading stored module config
,D/ChimeraCfgMgr( 6161): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6161): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6161): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6161): App measurement is starting up, version: 8489
I/GMPM-SVC( 6161): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1721): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1721): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6161): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6161): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6161): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6161): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6161): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6161): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7846 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 6161): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6161): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6161): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6161): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6161): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6161): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6161): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 6161): doRemovePackageData com.test.thalitest
,D/ChimeraCfgMgr( 6161): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6161): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7879 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  317): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 20.254ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 19.521ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.562ms
,E/BaseAppContext( 6161): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  885): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6161): CM callback handler got msg 524290
W/BaseAppContext( 6161): Using Auth Proxy for data requests.
W/BaseAppContext( 6161): Using Auth Proxy for data requests.
W/BaseAppContext( 6161): Using Auth Proxy for data requests.
W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,W/BaseAppContext( 6161): Using Auth Proxy for data requests.
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 6 
,W/DriveInitializer( 6161): Awaiting to be initialized
,W/DriveInitializer( 6161): Background init thread started
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7913 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 7846): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/DocListDatabase( 6161): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 6161): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 6161): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 6161): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 6161): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 6161): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 6161): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 6161): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 6161): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 6161): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 6161): Background init thread ended
E/SQLiteLog( 6161): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6161): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 6161): Process: com.google.android.gms, PID: 6161
E/AndroidRuntime( 6161): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6161): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6161): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6161): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6161): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6161): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6161): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 6161): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 6161): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 6161): disk I/O error (code 3850)
E/DriveAsyncService( 6161): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 6161): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 6161): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6161): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6161): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6161): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6161): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6161): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6161): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6161): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6161): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 6161): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 6161): Sending signal. PID: 6161 SIG: 9
,E/lowmemorykiller(  276): Error writing /proc/6161/oom_score_adj; errno=22
,E/lowmemorykiller(  276): Error writing /proc/6161/oom_score_adj; errno=22
,I/ActivityManager(  885): Killing 7660:com.android.vending/u0a32 (adj 15): empty #7
,D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2e84ed6d)
,D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiService(  885): Client connection lost with reason: 4
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 7846): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
,E/SQLiteLog( 7846): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
