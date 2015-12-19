#### Test 5065027869d93ea_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 6650): 
D/AndroidRuntime( 6650): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6650): CheckJNI is OFF
D/AndroidRuntime( 6650): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6669 uid=10393 gids={50393, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6650): Shutting down VM
V/ActivityManager(  894): Display changed displayId=0
W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6669): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6669): Time to load native libraries: 2 ms (timestamps 7514-7516)
,I/LibraryLoader( 6669): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6669): Binding Chromium to main looper Looper (main, tid 1) {2e246b57}
,I/LibraryLoader( 6669): Expected native library version number "",actual native library version number ""
,I/chromium( 6669): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6669): Initializing chromium process, singleProcess=true
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6669): ApplicationContext is null in ApplicationStatus
W/chromium( 6669): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6669): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6669): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6669): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6669): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6669): Local Branch: 
I/Adreno-EGL( 6669): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6669): Local Patches: NONE
I/Adreno-EGL( 6669): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d40281d:true
W/ActivityManager(  894): Activity pause timeout for ActivityRecord{62d3d2e u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6669): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6669): CordovaWebView is running on device made by: motorola
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6669): Render dirty regions requested: true
D/Atlas   ( 6669): Validating map...
W/chromium( 6669): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6669): Initialized EGL, version 1.4
D/OpenGLRenderer( 6669): Enabling debug mode 0
I/Keyboard.Facilitator( 1431): onFinishInput()
I/LaunchCheckinHandler(  894): Displayed com.test.thalitest/.MainActivity,cp,ca,1030
I/ActivityManager(  894): Displayed com.test.thalitest/.MainActivity: +956ms (total +1s30ms)
W/IInputConnectionWrapper( 6669): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6669): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6669): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6669): Cannot call determinedVisibility() - never saw a connection for the pid: 6669
,D/JsMessageQueue( 6669): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6669): JniHelper::setJavaVM(0xb7d2b310), pthread_self() = -1207196312
,D/JX-Cordova( 6669): jxcore cordova android initializing
,W/jxcore-log( 6669): Initializing JXcore engine
W/jxcore-log( 6669): JXcore engine is ready
,W/jxcore-log( 6669): Starting JXcore engine
,W/.test.thalitest( 6669): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10393 path="socket:[9436]" dev="sockfs" ino=9436 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6669): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10393 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6669): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10393 path="socket:[9530]" dev="sockfs" ino=9530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6669): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10393 path="socket:[26497]" dev="sockfs" ino=26497 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6669): Platform android
W/jxcore-log( 6669): 
W/jxcore-log( 6669): Process ARCH arm
W/jxcore-log( 6669): 
,I/jxcore-log( 6669): JXcore Cordova bridge is ready!
I/jxcore-log( 6669): 
,W/jxcore-log( 6669): JXcore engine is started
I/Choreographer( 6669): Skipped 171 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6669): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6669): Toggling radios to true
I/jxcore-log( 6669): 
,D/BluetoothAdapter( 6669): enable(): BT is already enabled..!
,D/WifiService(  894): New client listening to asynchronous messages
,D/WifiService(  894): setWifiEnabled: true pid=6669, uid=10393
E/WifiService(  894): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6669): Radios toggled
I/jxcore-log( 6669): 
D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6669): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Perf Test app loaded loaded
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): check test folder
I/jxcore-log( 6669): 
I/jxcore-log( 6669): found test : ./testFindPeers.js
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306):  STA Disconnected !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/wpa_supplicant( 1426): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/Tethering(  894): InitialState.processMessage what=4
,I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
D/Tethering(  894):  0
I/wpa_supplicant( 1426): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
,D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  894): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  894): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1426): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  304): Clearing all IP addresses on wlan0
D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 21
D/TCMD    (  455): Listening for incoming client connection request
,V/NativeCrypto( 1747): Read error: ssl=0xb8048f70: I/O error during system call, Connection timed out
V/NativeCrypto( 1747): SSL shutdown failed: ssl=0xb8048f70: I/O error during system call, Broken pipe
,I/jxcore-log( 6669): found test : ./testSendData.js
I/jxcore-log( 6669): 
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6731 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiMetrics(  894): connected time updated 122969
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/wpa_supplicant( 1426): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  894): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1426): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  894): ConnectModeState: Network connection lost 
E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1426): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6731): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  304): Clearing all IP addresses on wlan0
,D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  894): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/Choreographer( 6669): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/chromium( 6669): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  894): Explicit concurrent mark sweep GC freed 48512(2MB) AllocSpace objects, 3(234KB) LOS objects, 33% free, 20MB/30MB, paused 1.534ms total 138.993ms
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PhenotypeConfigurator( 1747): Scheduling Phenotype for one-off execution 1616 seconds from now (1450484677446)
,D/GetConfigurationSnapshotOperation( 1747): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 6731): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6731): MmsConfig.loadMmsSettings
I/Babel_SMS( 6731): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6731): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6731): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6731): MmsConfig.loadFromResources
,E/Babel_SMS( 6731): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6731): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/PhenotypeFlagCommitter( 1747): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1747): Using platform SSLCertificateSocketFactory
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  306): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1426): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  306): Event received = Trying to associate with
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  894): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  894): [1,450,484,677,583 ms] noteScanEnd no scan source
,E/WifiStateMachine(  894): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f4fe31b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 6731): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_Crash( 6731): startup - clean
,I/Babel   ( 6731): deleted: false for 0
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/TCMD    (  455): NL - Read 312 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 192 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
I/wpa_supplicant( 1426): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  306): Event received = Associated with c0:ff:d4
D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  0
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,I/ActivityManager(  894): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6780 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  894): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1426): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1426): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  306): Event received = WPA: Key negotiation com
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306):  STA Connected !!
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
E/MDMCTBK (  306): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
,D/MDMCTBK (  306): get_freq !!, resp=2412
I/MDMCTBK (  306): get_freq !!, Strip data
I/MDMCTBK (  306): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1211788832
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  894): Network connection established
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  894): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  894): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  894): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  894): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  304): Setting iface cfg
,E/WifiStateMachine(  894): Start Dhcp Watchdog 2
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend false
,W/ResourcesManager( 6780): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/wpa_supplicant( 1426): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  894): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1426): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@181ccb76 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@181ccb76 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6731): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6731): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6731): Unsupported mime video/mpeg2
,V/AlarmManager(  894): send {38d61554, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/VideoCapabilities( 6731): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6731): Unrecognized profile 2130706433 for video/avc
V/AlarmManager(  894): done {38d61554, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [39ms]
W/VideoCapabilities( 6731): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  894): Killing 6519:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/VideoCapabilities( 6731): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6731): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6804): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6804): version 5.5.6 starting
E/DHCPCD  ( 6804): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6804): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6804): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_6519/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 6547:android.process.acore/u0a7 (adj 15): empty #7
,I/vclib   ( 6731): onServiceConnected
W/Babel   ( 6731): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6804): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6804): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6804): wlan0: sending REQUEST (xid 0x7996aa61), next in 4.98 seconds
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_6547/cgroup.procs: No such file or directory
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6804): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6804): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6804): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 20
D/TCMD    (  455): Listening for incoming client connection request
,D/DHCPCD  ( 6804): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6804): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6804): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 6804): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1747): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  894): WifiStateMachine DHCP successful
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  894): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  894): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  894): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  894): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894):    accepting network in place of null
D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 19 Dec 2015 00:24:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450484678839], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450484678819]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1301): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1548): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/global frequency( 2590): no tags to log
D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 57167(3MB) AllocSpace objects, 36(1239KB) LOS objects, 39% free, 7MB/12MB, paused 1.147ms total 57.230ms
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/AlarmManager(  894): send {2b5a149b, *walarm*:com.google.android.intent.action.SEND_IDLE}
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  894): done {2b5a149b, *walarm*:com.google.android.intent.action.SEND_IDLE} [78ms]
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 3896(164KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 649us total 38.664ms
,I/art     (  894): Explicit concurrent mark sweep GC freed 31142(1554KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.551ms total 126.071ms
,I/art     ( 2590): Explicit concurrent mark sweep GC freed 42464(2MB) AllocSpace objects, 6(142KB) LOS objects, 40% free, 11MB/19MB, paused 1.079ms total 91.482ms
,D/BSUtils ( 2590): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2590): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2590): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2590): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2590): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2590): BcsDSCheckin.events found events 44
,D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/ConnectivityService(  894): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2590): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 2590): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6865 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1487): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2590): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2590): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2590): [debug] > CusSM.onRadioDown
,I/MusicStore( 6865): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6865): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524295
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6865): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6865): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6865): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6865): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6865): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6865): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6865): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6865): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6865): GMSCore installation verified
,I/ConfigStore( 6865): Config Database version: 1
,I/MediaRouter( 6865): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6865): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6865): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6865): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6912 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6865): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6865): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 6448:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_6448/cgroup.procs: No such file or directory
,V/Mms     ( 6912): mnc/mcc: 
,V/Mms     ( 6912): tag: int value: recipientLimit - 20
,V/Mms     ( 6912): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6912): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6912): tag: int value: maxSubjectLength - 80
V/Mms     ( 6912): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6912): tag: bool value: enableGroupMms - false
V/Mms     ( 6912):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6938 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6338:com.android.vending/u0a32 (adj 15): empty #7
,D/MMApiWSBase( 2590): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2590): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2590): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2590): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_6338/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6938): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6938): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6938): onReceive CONNECTIVITY_CHANGE networkType=1
,D/CheckinProvider(  894): 44 events delete 0 left
,I/ActivityManager(  894): Killing 6731:com.google.android.talk/u0a70 (adj 15): empty #7
,I/global frequency( 2590): BcsDSCheckin.events found events 0
D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_6731/cgroup.procs: No such file or directory
,I/global frequency( 2590): BcsTimer.onReceive checkin completed (0:ERROR_OK)
,D/Checkin ( 2590): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/CheckinService( 6382): Checkin interval check for package: unspecified last checkin: 1450484597657 min interval config: 0 actual interval: 83820
,I/CheckinService( 6382): Disabling old GoogleServicesFramework version
,I/CheckinService( 6382): Checking schedule, now: 1450484681506 next: 1450484627629
I/CheckinService( 6382): active receiver: enabled
,I/iu.SyncManager( 6382): SYNC; picasa accounts
,D/NetworkLogImpl( 6382): Loaded NetworkSpeedPredictor
,I/CheckinService( 6382): Preparing to send checkin request
,I/iu.Environment( 6382): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6382): Accumulating logs since 1450484594593
,I/iu.UploadsManager( 6382): num queued entries: 0
,I/iu.UploadsManager( 6382): num updated entries: 0
I/iu.SyncManager( 6382): NEXT; no task
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6966 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6382): Checkin reason type: 8 attempt count: 1
,D/WifiService(  894): New client listening to asynchronous messages
,E/ActivityThread( 6382): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 198406 ,futureTime: 9223372036854775807
D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 198407 ,futureTime: 9223372036854775807
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 198407 ,futureTime: 9223372036854775807
D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2590): [debug] > PollingManagerService, now: 198409 ,futureTime: 38962129
D/Central_PollingManager( 1487): now: 198411 ,futureTime: 86475457
D/Central_PollingManager( 1487): Polling alarm set to expire at: 86475457 Current Time: 198411
D/OtaApp  ( 2590): [debug] > Polling alarm set to expire at: 38962129 Current Time: 198411
,D/OtaApp  ( 2590): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2590): [debug] > CusSM.onRadioUp
,I/NetworkMonitor( 6865): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2590): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2590): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2590): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2590): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,W/DataUsage( 2590): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2590): set mOutstandingReq to true.
I/ Nonce  ( 2590):  Nonce getNonce 
I/ Nonce  ( 2590):  Nonce Request 
I/ Nonce  ( 2590):  Nonce execute Request 
,D/MMApiWebService( 2590): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2590): Not proxy app, so login/provision not allowed
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 3821(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 620us total 28.330ms
,I/art     (  894): Explicit concurrent mark sweep GC freed 14515(698KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.675ms total 135.088ms
,D/MMApiWebService( 2590): generating token using payload instead of using session token
,D/ Nonce  ( 2590):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2590): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6669): BLE supported!!
I/jxcore-log( 6669): 
D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6992 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6992): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7011 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7011): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7011): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7011): VM with version 2.1.0 has multidex support
,I/MultiDex( 7011): install
I/MultiDex( 7011): VM has multidex support, MultiDex support library is disabled.
,I/Babel_SMS( 6992): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6992): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6992): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6992): MmsConfig.loadFromDatabase
,V/JNIHelp ( 7011): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 6992): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6992): MmsConfig.loadFromResources
,E/Babel_SMS( 6992): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6992): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 7011): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7011): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37c1a28: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7011): Installed default security provider GmsCore_OpenSSL
,W/Settings( 6992): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6992): startup - clean
,I/art     ( 7011): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7011): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 6992): deleted: false for 0
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7048 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 7011): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6992): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6992): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6992): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6992): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6992): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6992): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6992): Unrecognized profile 2130706433 for video/avc
,D/WVCdm   (  309): Instantiating CDM.
I/WVCdm   (  309): CdmEngine::OpenSession
,I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6992): Unrecognized profile 2130706433 for video/avc
,I/ Nonce  ( 2590):  Nonce Reponse 
D/        ( 2590): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"5db68b80-b1ec-487d-89a6-708e9f86f439"}
D/MMApiWSBase( 2590): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2590):  Nonce Handle Reponse 
D/MMApiProvisionService( 2590): mOutstandingReq set to false
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
I/vclib   ( 6992): onServiceConnected
,W/Babel   ( 6992): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
,D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5600960
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb81d8bf8, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8194ca8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa830, idLength=0xb5500730
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=1507790048
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb82a0858
D/DrmWidevineDash(  309): message_length=1591, signature=0xb81940e8, signature_length=3041920788
,I/Babel   ( 6992): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  894): Killing 6780:com.motorola.context/u0a8 (adj 15): empty #7
,D/MMApiProvisionService( 2590):  pTime 1450461116267 sExp 172742 cTime 1450484682871 tTime 1450633858267
D/MMApiProvisionService( 2590):  No login Required 
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  894): failed to open /acct/uid_10008/pid_6780/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7048): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7048):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7048):   adb logcat -s GAv4
,W/GAv4    ( 7048): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7048): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7048): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/DataUsage( 2590): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,I/WebViewFactory( 7048): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7048): Time to load native libraries: 3 ms (timestamps 126-129)
I/LibraryLoader( 7048): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7048): Binding Chromium to main looper Looper (main, tid 1) {3efe5d58}
,I/LibraryLoader( 7048): Expected native library version number "",actual native library version number ""
I/chromium( 7048): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7048): Initializing chromium process, singleProcess=true
,W/art     ( 7048): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7048): ApplicationContext is null in ApplicationStatus
,W/chromium( 7048): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7048): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7048): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7048): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7048): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7048): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7048): Local Branch: 
I/Adreno-EGL( 7048): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7048): Local Patches: NONE
I/Adreno-EGL( 7048): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 7105): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/NSApplication( 7048): Starting up...
,W/AudioManagerAndroid( 7048): Requires BLUETOOTH permission
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7123 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 6865:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 26.162ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.637ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.663ms
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_6865/cgroup.procs: No such file or directory
,I/dex2oat ( 7105): dex2oat took 166.155ms (threads: 4)
,I/Adreno-EGL( 7011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7011): Local Branch: 
I/Adreno-EGL( 7011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7011): Local Patches: NONE
I/Adreno-EGL( 7011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7011): Local Branch: 
I/Adreno-EGL( 7011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7011): Local Patches: NONE
I/Adreno-EGL( 7011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  309): CdmEngine::OpenSession
I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  309): App is not loaded in QSEE
,E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7153 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6912:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  309): hlos api version =  9
,D/DrmWidevineDash(  309): tz api version =  8
,D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5600960
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb81e2ae0, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb827b330, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa870, idLength=0xbeaad2b0
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
,D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=2038942779
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81dfa30
D/DrmWidevineDash(  309): message_length=1626, signature=0xb82a0dc0, signature_length=3198866068
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_6912/cgroup.procs: No such file or directory
,W/ResourcesManager( 7153): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  309): CdmEngine::CloseSession
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7011): Local Branch: 
I/Adreno-EGL( 7011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7011): Local Patches: NONE
I/Adreno-EGL( 7011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7174 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Adreno-EGL( 7011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7011): Local Branch: 
I/Adreno-EGL( 7011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7011): Local Patches: NONE
I/Adreno-EGL( 7011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6382): Classify the device as Phone.
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7197 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6966:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7174): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 6938:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_6966/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_6938/cgroup.procs: No such file or directory
,I/MusicStore( 7197): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6382): Sending checkin request (9667 bytes)
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7197): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7197): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7197): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7197): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7197): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7197): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7197): GMSCore installation verified
,I/ConfigStore( 7197): Config Database version: 1
,I/MediaRouter( 7197): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7197): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7197): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7197): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7241 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7197): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  894): Explicit concurrent mark sweep GC freed 12498(604KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.679ms total 133.873ms
,I/GoogleURLConnFactory( 7197): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 6992:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7241): mnc/mcc: 
,V/Mms     ( 7241): tag: int value: recipientLimit - 20
V/Mms     ( 7241): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7241): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7241): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7241): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7241): tag: bool value: enableGroupMms - false
V/Mms     ( 7241):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinRequestBuilder( 6382): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_6992/cgroup.procs: No such file or directory
,E/ActivityThread( 6382): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7241): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7271 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7048:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7271): Register our PhoneStateListener
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311344, SEQNUM=4449, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13621, POWER_SUPPLY_CHARGE_COUNTER=-671, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_7048/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/MobileConnectivityChangeReceiver( 7271): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7271): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6382): Checkin interval check for package: unspecified last checkin: 1450484597657 min interval config: 0 actual interval: 88075
,I/ActivityManager(  894): Killing 7123:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7123/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6382): Classify the device as Phone.
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7292 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinTask( 6382): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6382): Checking schedule, now: 1450484685871 next: 1451085822858
I/CheckinService( 6382): active receiver: disabled
,I/CheckinService( 6382): Checking schedule, now: 1450484685892 next: 1451085822858
I/CheckinService( 6382): active receiver: disabled
,D/CheckinService( 6382): Recording last checkin time for package unspecified as 1450484685895
,I/ActivityManager(  894): Killing 7174:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  894): Killing 7153:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7174/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7153/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7310 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7197:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_7197/cgroup.procs: No such file or directory
,W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7310): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings
I/Babel_SMS( 7310): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7310): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7310): MmsConfig.loadFromResources
,E/Babel_SMS( 7310): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7310): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7310): startup - clean
,I/Babel   ( 7310): deleted: false for 0
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7344 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7310): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7310): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7310): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7310): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/vclib   ( 7310): onServiceConnected
W/ContextImpl( 7344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/Babel   ( 7310): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7344): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7344):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7344):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7344): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7344): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7310): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  894): Killing 7241:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7344): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_7241/cgroup.procs: No such file or directory
,I/WebViewFactory( 7344): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7344): Time to load native libraries: 2 ms (timestamps 3799-3801)
,I/LibraryLoader( 7344): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7344): Binding Chromium to main looper Looper (main, tid 1) {3efe5d58}
,I/LibraryLoader( 7344): Expected native library version number "",actual native library version number ""
I/chromium( 7344): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7344): Initializing chromium process, singleProcess=true
,W/art     ( 7344): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7344): ApplicationContext is null in ApplicationStatus
,W/chromium( 7344): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7344): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7344): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7344): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7344): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7344): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7344): Local Branch: 
I/Adreno-EGL( 7344): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7344): Local Patches: NONE
I/Adreno-EGL( 7344): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7344): Requires BLUETOOTH permission
,I/NSApplication( 7344): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7416 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7271:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7271/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7435 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 7292:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7292/cgroup.procs: No such file or directory
,W/ResourcesManager( 7435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7455 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 25.991ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.075ms
,I/ActivityManager(  894): Killing 7344:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 22.634ms
,I/ContactLocale( 7455): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 7310:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_7344/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2590): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7310/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2590): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2590): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2590): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2590): onServiceConnected()
,D/GetNotificationsWS( 2590): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2590): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2590): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7490 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7490): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7490): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7490): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7490): GMSCore installation verified
,I/ConfigStore( 7490): Config Database version: 1
,I/art     (  894): Explicit concurrent mark sweep GC freed 12473(651KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.531ms total 112.181ms
,I/MediaRouter( 7490): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7490): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7490): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7490): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7525 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7490): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7490): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 7416:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7525): mnc/mcc: 
,V/Mms     ( 7525): tag: int value: recipientLimit - 20
,V/Mms     ( 7525): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7525): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7525): tag: int value: maxSubjectLength - 80
V/Mms     ( 7525): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7525): tag: bool value: enableGroupMms - false
V/Mms     ( 7525):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7416/cgroup.procs: No such file or directory
,W/ResourcesManager( 7525): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7555 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7435:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7435/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7555): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7555): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6382): Checkin interval check for package: unspecified last checkin: 1450484685895 min interval config: 0 actual interval: 3171
,I/CheckinService( 6382): Checkin interval check for package: unspecified last checkin: 1450484685895 min interval config: 0 actual interval: 3175
,I/CheckinService( 6382): Checking schedule, now: 1450484689074 next: 1450484715858
,I/CheckinService( 6382): active receiver: disabled
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7576 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6382): Checking schedule, now: 1450484689144 next: 1450484715858
I/CheckinService( 6382): active receiver: disabled
,I/ActivityManager(  894): Killing 7455:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7455/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7596 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7490:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_7490/cgroup.procs: No such file or directory
,W/ResourcesManager( 7596): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7596): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7596): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7596): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7596): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7596): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7596): MmsConfig.loadFromResources
,E/Babel_SMS( 7596): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7596): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7596): startup - clean
,I/Babel   ( 7596): deleted: false for 0
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7627 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7596): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7596): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7596): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7596): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7596): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7596): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7596): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7596): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7596): onServiceConnected
,W/Babel   ( 7596): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7627): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7627): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7627): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7627):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7627):   adb logcat -s GAv4
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:33000 mC
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7627): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7627): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7627): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7596): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7627): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  894): Killing 7525:com.android.mms/u0a23 (adj 15): empty #7
,W/GAv4    ( 7627): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_7525/cgroup.procs: No such file or directory
,I/WebViewFactory( 7627): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7627): Time to load native libraries: 2 ms (timestamps 7085-7087)
I/LibraryLoader( 7627): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7627): Binding Chromium to main looper Looper (main, tid 1) {3efe5d58}
I/LibraryLoader( 7627): Expected native library version number "",actual native library version number ""
,I/chromium( 7627): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7627): Initializing chromium process, singleProcess=true
,W/art     ( 7627): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7627): ApplicationContext is null in ApplicationStatus
,W/chromium( 7627): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7627): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7627): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7627): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7627): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7627): Local Branch: 
I/Adreno-EGL( 7627): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7627): Local Patches: NONE
I/Adreno-EGL( 7627): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7627): Requires BLUETOOTH permission
,I/NSApplication( 7627): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7698 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7011:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_7011/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7717 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7555:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7555/cgroup.procs: No such file or directory
,W/ResourcesManager( 7717): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7737 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7596:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7737): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 7576:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2590): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7596/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7576/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2590): bindWebServices(): registering our AIDL callback...
I/SundryService( 2590): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2590): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2590): onServiceConnected()
D/GetNotificationsWS( 2590): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2590): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2590): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2590): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2590): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2590): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  894): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7772 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2590): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2590): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2590): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2590): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2590): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1431): onFinishInput()
,W/IInputConnectionWrapper( 6669): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  894): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,177
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,D/WearableService( 1747): callingUid 10016, callindPid: 1747
,E/MDM     ( 1747): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6382): Restart initialization of location
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  894): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  894): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5382754
,W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7805 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.506ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.061ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.806ms
,I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  894): Explicit concurrent mark sweep GC freed 19131(936KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 4.312ms total 139.531ms
,I/Launcher( 1583): Deferring update until onResume
,D/PhoneMonitor( 7805): Register our PhoneStateListener
,V/SetupWizard( 7805): Connected to Gservices successfully
,I/ActivityManager(  894): Killing 7627:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_7627/cgroup.procs: No such file or directory
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7830 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7860 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7877 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7698:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  894): Killing 7717:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7698/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7717/cgroup.procs: No such file or directory
,W/ResourcesManager( 7877): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7877): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7877): MmsConfig.loadMmsSettings
I/Babel_SMS( 7877): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7877): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7877): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7877): MmsConfig.loadFromResources
,E/Babel_SMS( 7877): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7877): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7877): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7877): startup - clean
,I/Babel   ( 7877): deleted: false for 0
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7910 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7910): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7910): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7910): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7910): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7877): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7877): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 6382): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6382): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@37ca1529 new=com.google.android.velvet.VelvetApplication@37ca1529
,I/Icing   ( 6382): updateResources: need to parse f{com.google.android.gms}
,I/VideoCapabilities( 7877): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7937 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 7937): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7830): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,I/ActivityManager(  894): Killing 7805:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/art     ( 7877): Suspending all threads took: 5.496ms
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7805/cgroup.procs: No such file or directory
,I/vclib   ( 7877): onServiceConnected
,W/Babel   ( 7877): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7877): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7877): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7877): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7877): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7877): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  894): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7970 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5687): Explicit concurrent mark sweep GC freed 3025(120KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 366us total 23.464ms
,I/ActivityManager(  894): Killing 7772:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7772/cgroup.procs: No such file or directory
,D/Finsky  ( 7970): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7970): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7970): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7970): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7970): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7970): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7970): Skipping gmscore version check
,D/Finsky  ( 7970): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7970): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  894): Killing 7860:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_7860/cgroup.procs: No such file or directory
,D/TaskPersister(  894): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6382): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6382): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  894): Killing 7910:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10027/pid_7910/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 7830:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_7830/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:33000 mC
,I/CheckinService( 6382): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310999, SEQNUM=4481, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-767, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1747): disconnect managed GoogleApiClient
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {10d1c357, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  894): send {20b07172, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  894): done {10d1c357, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  894): done {20b07172, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [37ms]
,I/CheckinService( 6382): Checkin interval check for package: unspecified last checkin: 1450484685895 min interval config: 0 actual interval: 43953
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [61ms]
,I/CheckinService( 6382): Checking schedule, now: 1450484729884 next: 1450484715858
I/CheckinService( 6382): active receiver: enabled
,I/CheckinService( 6382): Preparing to send checkin request
I/EventLogService( 6382): Accumulating logs since 1450484681659
,I/CheckinRequestBuilder( 6382): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6382): Failed to find provider info for com.google.android.wearable.settings
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/art     (  894): Explicit concurrent mark sweep GC freed 14990(772KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.679ms total 115.073ms
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  894): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8059 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8059): VM with version 2.1.0 has multidex support
I/MultiDex( 8059): install
I/MultiDex( 8059): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37c1a28: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8059): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1747): callingUid 10016, callindPid: 1747
,E/MDM     ( 1747): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6382): Restart initialization of location
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
,I/art     ( 8059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8059): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  309): Instantiating CDM.
,I/WVCdm   (  309): CdmEngine::OpenSession
I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5600960
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb81942e8, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8194ca8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa850, idLength=0xbeaad2b0
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=875347348
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb82a0858
D/DrmWidevineDash(  309): message_length=1591, signature=0xb81e2f10, signature_length=3198866068
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  309): CdmEngine::CloseSession
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8101): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8101): dex2oat took 78.167ms (threads: 4)
,I/Adreno-EGL( 8059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8059): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8059): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8059): Local Branch: 
I/Adreno-EGL( 8059): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8059): Local Patches: NONE
I/Adreno-EGL( 8059): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8059): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8059): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8059): Local Branch: 
I/Adreno-EGL( 8059): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8059): Local Patches: NONE
I/Adreno-EGL( 8059): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  309): CdmEngine::OpenSession
I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5500960
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb81792b8, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8194ca8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa870, idLength=0xb1416730
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=2555364427
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb82a0858
D/DrmWidevineDash(  309): message_length=1626, signature=0xb81e2f10, signature_length=2973853460
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8059): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8059): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8059): Local Branch: 
I/Adreno-EGL( 8059): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8059): Local Patches: NONE
I/Adreno-EGL( 8059): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8059): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8059): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8059): Local Branch: 
I/Adreno-EGL( 8059): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8059): Local Patches: NONE
I/Adreno-EGL( 8059): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6382): Classify the device as Phone.
,I/CheckinTask( 6382): Sending checkin request (9668 bytes)
,I/CheckinRequestBuilder( 6382): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6382): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6382): Classify the device as Phone.
,I/CheckinTask( 6382): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6382): Checking schedule, now: 1450484733851 next: 1451085870846
I/CheckinService( 6382): active receiver: disabled
,D/CheckinService( 6382): Recording last checkin time for package unspecified as 1450484733864
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8132 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8132): Register our PhoneStateListener
,V/SetupWizard( 8132): Connected to Gservices successfully
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  894): Killing 7937:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  894): Killing 7737:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7937/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7737/cgroup.procs: No such file or directory
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8154 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  894): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  894): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@30b5e993
,I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1583): Deferring update until onResume
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8191 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8213 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7970:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 27.181ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.600ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.007ms
,W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_7970/cgroup.procs: No such file or directory
,W/ResourcesManager( 7877): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7877): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8236 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8132:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8213): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_8132/cgroup.procs: No such file or directory
,W/asset   ( 8236): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8236): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8236): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6382): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6382): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@37ca1529 new=com.google.android.velvet.VelvetApplication@37ca1529
,I/UpdateIcingCorporaServi( 8154): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6382): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8262 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8154): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 74812(4MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 15MB/25MB, paused 1.139ms total 104.832ms
,I/art     (  894): Explicit concurrent mark sweep GC freed 17330(891KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.601ms total 120.805ms
,I/ActivityManager(  894): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8287 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8059:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_8059/cgroup.procs: No such file or directory
,D/Finsky  ( 8287): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8287): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8287): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8287): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8287): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 8287): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8287): Skipping gmscore version check
,I/ActivityManager(  894): Killing 8191:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_8191/cgroup.procs: No such file or directory
,D/Finsky  ( 8287): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8287): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6382): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6382): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  894): Killing 8236:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10027/pid_8236/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 7877:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7877/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1431): run()
I/Keyboard.Facilitator( 1431): flushDynamicLanguageModels()
,I/ConfigService( 1747): onCreate
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1747): onDestroy
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311481, SEQNUM=4505, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-887, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6669): Connected to the server!
I/jxcore-log( 6669): 
,I/chromium( 6669): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 6
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {4916a90, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  894): done {4916a90, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6669): --- start :testSendData.js---
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): daya100000
I/jxcore-log( 6669): 
I/jxcore-log( 6669): check server
I/jxcore-log( 6669): 
I/jxcore-log( 6669): serverPort is 40321
I/jxcore-log( 6669): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT5534
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6669): bind: Binding a new listener
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6669): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6669): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5534","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): start: OK
I/io.jxcore.node.ConnectionHelper( 6669): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT5534
,D/BluetoothManagerService(  894): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6669): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5534","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6669): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5534","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6669): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5534","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  894): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f295b496 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f295b496 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service
,D/WifiP2pService(  894): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): start: Starting P2P device discovery...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6669): start: OK
,I/jxcore-log( 6669): StartBroadcasting started ok
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:28:52.415Z SendDataTCPServer.js: TCP/IP server is bound to port: 40321
I/jxcore-log( 6669): 
I/chromium( 6669): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6669): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6669): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6669): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  894):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  894):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : samsung-SM-A300FU_PT2588, Available: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[1]: 08:EC:A9:50:75:41
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:28:54.126Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:28:54.131Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:28:54.131Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 799)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] is available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":true}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): Found peer : samsung-SM-A500FU_PT6283, Available: true
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : samsung-SM-G900F_PT838, Available: true
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : samsung-SM-A500FU_PT7600, Available: true
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3689c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,D/BluetoothManagerService(  894): Message: 20
,D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f18cdfd:true
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 08:EC:A9:50:75:41
,I/ActivityManager(  894): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8377 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2455): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e246b57
,D/BluetoothMetrics( 2455): btclass5a020c
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/ResourcesManager( 8377): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50cc543:true
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
I/ActivityManager(  894): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8417 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 799)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 799)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 800)
,I/ActivityManager(  894): Killing 8154:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 800)
D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 801)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 44775
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_8154/cgroup.procs: No such file or directory
,W/ResourcesManager( 8417): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT5596","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : samsung-SM-A300FU_PT5596, Available: true
I/jxcore-log( 6669): 
,D/BluetoothManagerService(  894): Message: 20
,D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b9fd43e:true
,I/ActivityManager(  894): Killing 8213:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_8213/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 44775 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 6669): 2015-12-19T00:29:01.687Z SendDataConnector.js: CLIENT connected to 44775, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:01.687Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.OutgoingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 44775
,D/io.jxcore.node.OutgoingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6669): Exiting thread (ID: 801)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 803, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 802, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:01.700Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 6669): 2015-12-19T00:29:02.487Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:02.529Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 1 c0
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:29:02.668Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:02.767Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6669): 2015-12-19T00:29:02.915Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.119Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.208Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.250Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.332Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.478Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:03.479Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:03.481Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:03.481Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 6669): close
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 803
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 802
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 802, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 803, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 803, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 802, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:03.503Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[2]: 7C:F9:0E:37:96:AB
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:03.507Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:03.507Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:03.507Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 804)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  894):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  894):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2462 a2
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8455 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23c0f64a:true
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2455): Removing bonded device:7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BluetoothMetrics( 2455): btclass5a020c
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 804)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 805)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 805)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 804)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 805)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 805)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 805)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 806)
D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 49214
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 807)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 807)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 807)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 807)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 807
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 807)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 6669): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 807)
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 2
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8489 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 808)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log( 6669): 2015-12-19T00:29:06.726Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 808)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 810, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 809, name: Sender)
,I/BluetoothClassifier( 8455): Bluetooth Device Name: A5-1
,I/ActivityManager(  894): Killing 8262:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_8262/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 8287:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_8287/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 49214 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 6669): 2015-12-19T00:29:06.916Z SendDataConnector.js: CLIENT connected to 49214, error: null
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:06.916Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 49214
D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 806)
D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 811, name: Sender)
I/jxcore-log( 6669): 2015-12-19T00:29:06.923Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 812, name: Receiver)
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3689c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: A3-1
,I/jxcore-log( 6669): 2015-12-19T00:29:07.721Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.724Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.729Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.734Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.741Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.746Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.752Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.789Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.793Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.797Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6669): 2015-12-19T00:29:07.811Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.830Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.879Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.917Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.950Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:07.980Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.018Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.042Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.116Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.126Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6669): 2015-12-19T00:29:08.159Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.161Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.193Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.256Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.287Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.292Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.327Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.358Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.367Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.407Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.437Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6669): 2015-12-19T00:29:08.451Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.478Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.555Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.589Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.590Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.600Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.637Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.723Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.757Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.798Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.823Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.883Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.908Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:08.917Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 810, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 808
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 810
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 809
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 809, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 810, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 809, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:09.184Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:09.186Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:09.189Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:09.193Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:09.193Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 6669): close
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 812
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 811
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 811, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 812, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 811, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 812, name: Receiver)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 6669): 2015-12-19T00:29:09.212Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6669): 
I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[3]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:09.213Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:09.213Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:09.213Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 813)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : samsung-SM-G900F_PT6107, Available: true
I/jxcore-log( 6669): 
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 813)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 814)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 814)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 813)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 814)
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36a5c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36a5c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 81 bytes successfully (thread ID: 814)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 814)
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 815)
D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 54154
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 54154 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 6669): 2015-12-19T00:29:13.759Z SendDataConnector.js: CLIENT connected to 54154, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:13.760Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.OutgoingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 54154
D/io.jxcore.node.OutgoingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6669): Exiting thread (ID: 815)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 817, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 816, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:13.779Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:15.498Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:15.676Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:15.811Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.038Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.049Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.093Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.098Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.138Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.144Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.168Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:16.169Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:16.169Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:16.169Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 6669): close
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 817
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 816
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 816, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 817, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 816, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 817, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:29:16.192Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6669): 
I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[4]: 7C:F9:0E:51:18:22
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:16.194Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:16.194Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:16.194Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 818)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36a5c rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: S5-1
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 818)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 819)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 819)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 818)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 819)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 819)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 819)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 820)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 41521
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 821)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 821)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 821
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6669): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 821)
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 822)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,I/jxcore-log( 6669): 2015-12-19T00:29:22.600Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 822)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 823, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 824, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 41521 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 6669): 2015-12-19T00:29:22.728Z SendDataConnector.js: CLIENT connected to 41521, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:22.729Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 41521
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 820)
,I/jxcore-log( 6669): 2015-12-19T00:29:22.742Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 826, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 825, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:23.327Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.410Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.535Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.547Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.603Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.636Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.784Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.817Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.919Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6669): 2015-12-19T00:29:23.928Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.938Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:23.974Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.082Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.096Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.122Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.135Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6669): 2015-12-19T00:29:24.145Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.153Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.187Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.286Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.311Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.323Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.636Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.784Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.818Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.855Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.863Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6669): 2015-12-19T00:29:24.871Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:24.963Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.020Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.058Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.128Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.368Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.377Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.410Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.469Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.549Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.560Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.575Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.617Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.630Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.670Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.772Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.783Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.791Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.936Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.949Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.961Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.975Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:25.998Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.004Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.075Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.108Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.113Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.113Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:26.114Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:26.114Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 6669): close
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 826
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
,W/bt-btif ( 2455): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 824, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 825
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 825, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...,
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 826, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 822
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 824
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 823
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 824, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 823, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 825, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 826, name: Receiver)
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 823, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:26.152Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6669): 
I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[5]: 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:26.154Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:26.154Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:26.154Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 827)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 6669): 2015-12-19T00:29:26.166Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36c1c rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT2457","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : LGE-LG-D722_PT2457, Available: true
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 2 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,W/bt-sdp  ( 2455): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 2455): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2455): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 827)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 827)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/jxcore-log( 6669): 2015-12-19T00:29:33.513Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] failed
I/jxcore-log( 6669): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 827)
,I/jxcore-log( 6669): 2015-12-19T00:29:33.520Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] failed
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:33.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2462 0a
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 829)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 829)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 829
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 829)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] is available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : LGE-LG-H815_PT2685, Available: true
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 830)
,I/jxcore-log( 6669): 2015-12-19T00:29:34.185Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 830)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 832, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 831, name: Sender)
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:29:34.922Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:34.927Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:34.945Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:34.950Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:34.954Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:34.970Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: RESTARTING
,D/WifiP2pService(  894): InactiveState{ when=0 what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1426): P2P-FIND-STOPPED 
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  306): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/WifiP2pService(  894): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): discovery change broadcast false
,D/WifiP2pService(  894): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/WifiP2pService(  894): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/WifiP2pService(  894): InactiveState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6669): 2015-12-19T00:29:35.081Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 6669): 2015-12-19T00:29:35.107Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.144Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.177Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.184Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.218Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.246Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.252Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.287Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.307Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.313Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.347Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.355Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.387Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.427Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.474Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:35.508Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 832, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 830
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 832
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 831
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 832, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 831, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 831, name: Sender)
,W/bt-rfcomm( 2455): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2455): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 6669): 2015-12-19T00:29:35.554Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:38.524Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:38.524Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Start timer timeout, starting now...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: A3-1
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 833)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 833)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 833)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 833
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 833)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 833)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 834)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6669): 2015-12-19T00:29:40.351Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 834)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 835, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 836, name: Receiver)
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,I/jxcore-log( 6669): 2015-12-19T00:29:41.135Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.140Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.147Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.153Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.159Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.165Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.172Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.207Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.214Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.249Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.289Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.295Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.302Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.308Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.336Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.352Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.358Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.398Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.407Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.420Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.457Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.565Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.598Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.602Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.608Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.652Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.688Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.727Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.736Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.768Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.793Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6669): 
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6669): 2015-12-19T00:29:41.836Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,W/bt-btif ( 2455): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 836, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 834
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 836
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 835
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 835, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 836, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 835, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:41.882Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,W/bt-rfcomm( 2455): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2455): RFCOMM_DisconnectInd LCID:0x4e
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 6669): 2015-12-19T00:29:43.530Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:43.531Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:43.531Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:43.533Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 837)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6669): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3689c rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2462 a2
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 837)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 838)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 838)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 837)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 838)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 83 bytes successfully (thread ID: 838)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 838)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 839)
D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 43385
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 43385 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 6669): 2015-12-19T00:29:52.619Z SendDataConnector.js: CLIENT connected to 43385, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:52.620Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.OutgoingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 43385
,D/io.jxcore.node.OutgoingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6669): Exiting thread (ID: 839)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 841, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 840, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:29:52.638Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6669): 2015-12-19T00:29:53.420Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 6669): 2015-12-19T00:29:53.459Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:53.464Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9856
,I/jxcore-log( 6669): 2015-12-19T00:29:53.567Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 6669): 2015-12-19T00:29:53.649Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:53.727Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:53.800Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:29:53.970Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.142Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.225Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.226Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.232Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.232Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 6669): close
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 841
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 840
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 840, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 841, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 840, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 841, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:29:54.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[6]: B0:C5:59:3F:75:69
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:54.259Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:54.260Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:54.261Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 842)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 842)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 843)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 843)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 842)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 843)
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 82 bytes successfully (thread ID: 843)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 843)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 844)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 44885
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 44885 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 6669): 2015-12-19T00:29:58.168Z SendDataConnector.js: CLIENT connected to 44885, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:58.168Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.OutgoingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 44885
,D/io.jxcore.node.OutgoingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6669): Exiting thread (ID: 844)
,I/jxcore-log( 6669): 2015-12-19T00:29:58.182Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 846, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 845, name: Sender)
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/art     (  894): Explicit concurrent mark sweep GC freed 23609(1364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.657ms total 122.502ms
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 6669): 2015-12-19T00:29:58.938Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.012Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.018Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.030Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.066Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.072Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.115Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.156Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.251Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.257Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:29:59.257Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:59.258Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:59.258Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 6669): close
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 846
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 845
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 845, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 846, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 845, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 846, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:29:59.284Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 6669): 
I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[7]: F8:95:C7:87:85:54
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:59.285Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:59.286Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:29:59.286Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 847)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {12026e08, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  894): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8685 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [95ms]
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/GAv4    ( 8685): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8685):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8685):   adb logcat -s GAv4
,W/GAv4    ( 8685): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8685): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8685): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  894): done {12026e08, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [309ms]
,I/ActivityManager(  894): Killing 6382:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  894): Client connection lost with reason: 4
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_6382/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 847)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 848)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 848)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 847)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 848)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 4 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 848)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 848)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 849)
D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 42110
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 850)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 850)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 850)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 850)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 850
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 850)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 850)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6669): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 851)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6669): 2015-12-19T00:30:02.289Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 851)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 852, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 853, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 42110 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 6669): 2015-12-19T00:30:02.415Z SendDataConnector.js: CLIENT connected to 42110, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:02.416Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 42110
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 849)
,I/jxcore-log( 6669): 2015-12-19T00:30:02.430Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 855, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 854, name: Sender)
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3715c rs_disc_pending=0
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6669): 2015-12-19T00:30:03.585Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.590Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.597Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.687Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 6669): 2015-12-19T00:30:03.854Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.885Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.897Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:03.967Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.001Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.006Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.015Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.020Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.049Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.053Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.089Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.094Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.138Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.144Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.177Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.201Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.246Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.322Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.519Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.519Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.526Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.528Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
,I/io.jxcore.node.IncomingSocketThread( 6669): close
,D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 855
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 854
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 854, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 855, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 854, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 855, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:30:04.558Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[8]: F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.561Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.562Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.563Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 6669): 2015-12-19T00:30:04.574Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6669): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 856)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6669): 2015-12-19T00:30:04.589Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.593Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:04.748Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:05.109Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:05.233Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:05.483Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 6669): 2015-12-19T00:30:05.983Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:06.108Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6669): 
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6669): 2015-12-19T00:30:06.483Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:06.608Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:07.672Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:07.678Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:08.616Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:09.503Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:09.511Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:09.947Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:09.954Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6669): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6669): 2015-12-19T00:30:10.395Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:10.427Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:10.912Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:11.819Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:11.824Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:11.828Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:11.834Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:11.867Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:12.338Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:12.343Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:12.815Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): invalid rfc slot id: 13
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 853, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 851
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 853
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 852
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams,
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 852, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 853, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 852, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:30:12.870Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [7c:f9:0e:34:8a:a0]: 0, 0, 0
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 857)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 857)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 81 bytes successfully (thread ID: 857)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 857)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 857
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 857)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 857)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 858)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
,I/jxcore-log( 6669): 2015-12-19T00:30:15.338Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 858)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 860, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 859, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:30:16.337Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.389Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.394Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.399Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.403Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.408Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.415Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.591Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.627Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.788Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.893Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.900Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.937Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:16.982Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.018Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.025Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.057Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6669): 
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G3s-1
,I/jxcore-log( 6669): 2015-12-19T00:30:17.114Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.172Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.207Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.365Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.497Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.538Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:17.578Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,I/ActivityManager(  894): Waited long enough for: ServiceRecord{1e1c07c6 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT6618","peerAvailable":true}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): Found peer : LGE-Nexus 5_PT6618, Available: true
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 860, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 858
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 860
,D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 859
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 860, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 859, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 859, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:30:19.113Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,W/bt-rfcomm( 2455): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2455): RFCOMM_DisconnectInd LCID:0x49
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionTimeout: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/jxcore-log( 6669): 2015-12-19T00:30:19.570Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:19.570Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:19.571Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pManager( 6669): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: S5-1
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] not available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] not available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":false}]
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":false}]
I/jxcore-log( 6669): 
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,I/jxcore-log( 6669): 2015-12-19T00:30:24.570Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:24.571Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 6 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] is available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":true}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): Found peer : HTC-HTC One M8s_PT6420, Available: true
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5596","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] already in the list, will not add again
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:30:29.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:29.573Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:29.573Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:29.574Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 862)
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 6 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionTimeout: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/jxcore-log( 6669): 2015-12-19T00:30:44.583Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:44.584Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:44.584Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:49.585Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:30:49.586Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: RESTARTING
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=139268 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1426): P2P-FIND-STOPPED 
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  306): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  894): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): discovery change broadcast false
,D/WifiP2pService(  894): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  894): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=1
,E/bt-btif ( 2455): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): invalid rfc slot id: 18
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2455): onReceive
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 856)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 856)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 856)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 856)
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:30:54.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:54.587Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:54.587Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:30:54.587Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 864)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6669): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Start timer timeout, starting now...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 7 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 7 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 8 c0
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionTimeout: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/jxcore-log( 6669): 2015-12-19T00:31:09.595Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:09.595Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] timed out
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:09.596Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] is available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":true}]
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] is available
,I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":true}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): Found peer : samsung-SM-N910C_PT3595, Available: true
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":true}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : LGE-LG-D855_PT7127, Available: true
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 8 
,I/jxcore-log( 6669): 2015-12-19T00:31:14.601Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:14.602Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:31:19.604Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:19.605Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:19.605Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:19.605Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 866)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6669): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
,W/bt-sdp  ( 2455): SDP - Rcvd conn cnf with error: 0x8  CID 0x48
,E/bt-btif ( 2455): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2455): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 862)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 862)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 862)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 862)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/jxcore-log( 6669): 2015-12-19T00:31:26.358Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:26.359Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:26.359Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,E/bt-rfcomm( 2455): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
,E/bt-btif ( 2455): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2455): invalid rfc slot id: 22
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,E/bt-rfcomm( 2455): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2455): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2455): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 866)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 866)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 866)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 866)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6669): 2015-12-19T00:31:31.360Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:31.361Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 864)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 864)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 868)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 864)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 868)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 868)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: RESTARTING
,D/WifiP2pService(  894): InactiveState{ when=0 what=139268 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1426): P2P-FIND-STOPPED 
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  306): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1426): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  894): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): discovery change broadcast false
,D/WifiP2pService(  894): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  894):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  894):  primary type: null
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 0
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 0
D/WifiP2pService(  894):  status: 4
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:31:36.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:36.401Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:36.401Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:36.401Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 869)
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 869)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 870)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 870)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 869)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 870)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 870)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 870)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 871)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 60593
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 60593 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 6669): 2015-12-19T00:31:39.269Z SendDataConnector.js: CLIENT connected to 60593, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:39.269Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.OutgoingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 60593
,D/io.jxcore.node.OutgoingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6669): Exiting thread (ID: 871)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 873, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:31:39.288Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 872, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:31:39.998Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:40.069Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:40.237Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6669): 2015-12-19T00:31:40.375Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:40.461Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [b0:c5:59:3f:75:69]: 7, f, 6109
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 6669): 2015-12-19T00:31:40.846Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:40.877Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:40.963Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:41.008Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 874)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 874)
,I/jxcore-log( 6669): 2015-12-19T00:31:41.130Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:41.130Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:41.131Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:41.131Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 6669): close
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 873
D/io.jxcore.node.OutgoingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 872
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 872, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 873, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 872, name: Sender)
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 873, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:31:41.162Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6669): 
I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[9]: 34:FC:EF:11:AE:67
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:41.169Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:41.169Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:41.171Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 875)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 82 bytes successfully (thread ID: 874)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 874)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 874
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 874)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 874)
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":true}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 876)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 876)
,I/jxcore-log( 6669): 2015-12-19T00:31:41.207Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 877, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 878, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Start timer timeout, starting now...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139265 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139265 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  894): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 9 c0
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  894):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  894):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=49 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,I/jxcore-log( 6669): 2015-12-19T00:31:42.405Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.414Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.419Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.434Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.506Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.512Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.518Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.557Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/jxcore-log( 6669): 2015-12-19T00:31:42.666Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.673Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.708Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.712Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.719Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.757Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.787Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.794Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.828Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:42.842Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6669): 
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=0
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6669): 2015-12-19T00:31:43.112Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6669): 
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,I/jxcore-log( 6669): 2015-12-19T00:31:43.245Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 875)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 879)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 879)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 875)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 879)
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,I/wpa_supplicant( 1426): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service discovery started successfully
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:31:43.631Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:43.637Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:43.705Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6669): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 879)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 879)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 880)
D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 48574
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36f9c rs_disc_pending=1
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 881)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 881)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 77 bytes successfully (thread ID: 881)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 881)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 881
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 881)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 881)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: We have an outgoing connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6669): onConnected: Already connected with peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 3
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 882)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6669): 2015-12-19T00:31:43.852Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 882)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 883, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 884, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:31:43.908Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 6669): 
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 48574 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 6669): 2015-12-19T00:31:44.022Z SendDataConnector.js: CLIENT connected to 48574, error: null
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.022Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 48574
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 880)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 886, name: Receiver)
,I/jxcore-log( 6669): 2015-12-19T00:31:44.040Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 885, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:31:44.528Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.531Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.595Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.627Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6669): 2015-12-19T00:31:44.667Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.674Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.678Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.686Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.691Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.718Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.766Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.771Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.805Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): invalid rfc slot id: 19
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 878, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 876
,D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 878
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 877
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 878, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 877, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 877, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:31:44.826Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.832Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.835Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:44.838Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6669): 
,W/bt-rfcomm( 2455): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 2455): RFCOMM_DisconnectInd LCID:0x41
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6669): 2015-12-19T00:31:44.963Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/jxcore-log( 6669): 2015-12-19T00:31:45.041Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6669): 
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: G4-1
,I/jxcore-log( 6669): 2015-12-19T00:31:45.102Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.138Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6669): 
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3715c rs_disc_pending=0
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6669): 2015-12-19T00:31:45.178Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.184Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 6669): 2015-12-19T00:31:45.219Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  894):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-1ms what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:31:45.382Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.417Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.441Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.447Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":true}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.689Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.722Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.757Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.803Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.814Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.819Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.866Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.897Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 9 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.957Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.972Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.977Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.990Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:45.995Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.028Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.061Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6669): 
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6669): 2015-12-19T00:31:46.117Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.268Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.296Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.428Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.467Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.507Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.518Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.547Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.588Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.594Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6669): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 10 c
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,I/jxcore-log( 6669): 2015-12-19T00:31:46.723Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.792Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.808Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.809Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6669): 
I/jxcore-log( 6669): oneRoundDownNow
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:46.809Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:46.809Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6669): 
D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.IncomingSocketThread( 6669): close
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 886
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 885
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 885, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 886, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 886, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 885, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:31:46.838Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): ---- round done--------
I/jxcore-log( 6669): 
I/jxcore-log( 6669): startWithNextDevice
I/jxcore-log( 6669): 
I/jxcore-log( 6669): device[10]: 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:46.839Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:46.839Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:46.839Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log( 6669): 2015-12-19T00:31:46.849Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6669): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 887)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3715c rs_disc_pending=1
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  894): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] is available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":true}]
I/jxcore-log( 6669): 
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-btif ( 2455): invalid rfc slot id: 25
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 884, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 882
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 884
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 883
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 884, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 883, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 883, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:31:47.458Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3715c rs_disc_pending=1
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2455): onReceive
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2455): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,E/bt-btif ( 2455): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2455): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2455): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2455): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2455): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2455): StableState(): Entering Off State
,D/BluetoothMetrics( 2455): btclass5a020c
,D/Checkin ( 2455): publish the event [tag = MOT_BT event name = PAIRING]
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  894):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 392
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED ,
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1426): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT2457","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT5596","peerAvailable":false}]
I/jxcore-log( 6669): 
,I/wpa_supplicant( 1426): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  894): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  894):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  894):  primary type: 10-0050F204-5
D/WifiP2pService(  894):  secondary type: null
D/WifiP2pService(  894):  wps: 4488
D/WifiP2pService(  894):  grpcapab: 0
D/WifiP2pService(  894):  devcapab: 37
D/WifiP2pService(  894):  status: 3
D/WifiP2pService(  894):  wfdInfo: null
D/WifiP2pService(  894):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): InactiveState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): restart: Restarting...
,D/WifiP2pService(  894): InactiveState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState clear service request
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,--------- beginning of crash
F/libc    ( 1426): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1426 (wpa_supplicant)
I/libc    ( 1426): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  894): InactiveState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState add service request
,D/WifiP2pManager( 6669): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Service request added successfully
,E/QC-QMI  (  393): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  393): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  393): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  393): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  393): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2455): invalid rfc slot id: 28
,D/BluetoothMapService( 2455): onReceive
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 887)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 887)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 887)
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: HTC One M8s
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/jxcore-log( 6669): 2015-12-19T00:31:54.874Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] failed
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:54.874Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] failed
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:31:54.875Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 887)
,D/WifiP2pService(  894): InactiveState{ when=0 what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6669): Failed to start the service discovery, got error code: 3
,I/jxcore-log( 6669): 2015-12-19T00:31:59.875Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:31:59.876Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/ActivityManager(  894): Waited long enough for: ServiceRecord{20e2123 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:32:04.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:04.882Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:04.882Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:04.882Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 889)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6669): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2455): SDP - Rcvd conn cnf with error: 0x1f  CID 0x49
,E/bt-btif ( 2455): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2455): invalid rfc slot id: 29
,W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2455): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2455): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2455): invalid rfc slot id: 30
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 889)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Maximum number of allowed retries (0) reached, giving up... (thread ID: 889)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 889)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/jxcore-log( 6669): 2015-12-19T00:32:11.576Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] failed
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:11.577Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] failed
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:11.577Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6669): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): shutdown (thread ID: 889)
,I/jxcore-log( 6669): 2015-12-19T00:32:16.577Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:16.578Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,D/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6669): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 6669): 2015-12-19T00:32:21.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:21.580Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:21.580Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:21.580Z SendDataConnector.js: do connect now
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 6669): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 891)
W/BluetoothAdapter( 6669): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2455): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver( 8455): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8455): Bluetooth Device Name: HTC One M8s
,W/bt-sdp  ( 2455): process_service_search_attr_rsp
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 891)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 892)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Outgoing connection initialized (*handshake* thread ID: 892)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Exiting thread (thread ID: 891)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 892)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): onBytesRead: Read 81 bytes successfully (thread ID: 892)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6669): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 892)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6669): Entering thread (ID: 893)
,D/io.jxcore.node.OutgoingSocketThread( 6669): Server socket local port: 35749
I/io.jxcore.node.OutgoingSocketThread( 6669): Now accepting connections...
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection initialized (thread ID: 894)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Entering thread (ID: 894)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesRead: Read 81 bytes successfully (thread ID: 894)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): onBytesWritten: 81 bytes successfully written (thread ID: 894)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): removeThreadFromList: Removing thread with ID 894
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Handshake thread disposed (thread ID: 894)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6669): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6669): Exiting thread (ID: 894)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6669): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: We have an outgoing connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 6669): onConnected: Already connected with peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6669): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], created successfully
D/io.jxcore.node.ConnectionHelper( 6669): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6669): Entering thread (ID: 895)
,I/io.jxcore.node.IncomingSocketThread( 6669): Local host address: localhost/127.0.0.1, port: 40321
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6669): 2015-12-19T00:32:23.303Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6669): 
,I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 895)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 897, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 896, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 6669): onListeningForIncomingConnections: Outgoing connection is using port 35749 (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log( 6669): 2015-12-19T00:32:23.439Z SendDataConnector.js: CLIENT connected to 35749, error: null
I/jxcore-log( 6669): 
I/jxcore-log( 6669): 2015-12-19T00:32:23.440Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6669): 
,I/io.jxcore.node.IncomingSocketThread( 6669): Incoming data from address: /127.0.0.1, port: 35749
,D/io.jxcore.node.IncomingSocketThread( 6669): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6669): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6669): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6669): Exiting thread (ID: 893)
,I/jxcore-log( 6669): 2015-12-19T00:32:23.454Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6669): 
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 899, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6669): Entering thread (ID: 898, name: Sender)
,I/jxcore-log( 6669): 2015-12-19T00:32:24.054Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.064Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.102Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.119Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6669): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): checkListForExpiredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): modifyListOfDiscoveredPeers: Removed [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":false}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): Found peer : samsung-SM-N910C_PT3595, Available: false
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":false}]
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":false}]
I/jxcore-log( 6669): 
I/jxcore-log( 6669): Found peer : LGE-LG-D855_PT7127, Available: false
I/jxcore-log( 6669): 
I/io.jxcore.node.ConnectionHelper( 6669): onPeerLost: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618]
,D/io.jxcore.node.ConnectionHelper( 6669): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6669): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] removed
D/io.jxcore.node.ConnectionHelper( 6669): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT6618] not available
I/jxcore-log( 6669): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT6618","peerAvailable":false}]
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.143Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.160Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.199Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.238Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.263Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.274Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6669): 2015-12-19T00:32:24.286Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.296Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.330Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.367Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.379Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.394Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.401Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.430Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.467Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.500Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6669): 
,I/jxcore-log( 6669): 2015-12-19T00:32:24.515Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6669): 
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,E/WifiStateMachine(  894): Connection lost, restart supplicant
,E/WifiStateMachine(  894): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  894): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  894): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  894): failed to set BSSID: any
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  304): Clearing all IP addresses on wlan0
,D/TCMD    (  455): NL - Read 60 bytes from update socket.
,D/TCMD    (  455): NL - ignore NL message, type = 21
,D/TCMD    (  455): Listening for incoming client connection request
,V/NativeCrypto( 1747): Read error: ssl=0xb80b09a0: I/O error during system call, Connection timed out
I/jxcore-log( 6669): 2015-12-19T00:32:24.617Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6669): 
,V/NativeCrypto( 1747): SSL shutdown failed: ssl=0xb80b09a0: I/O error during system call, Broken pipe
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: RESTARTING
D/WifiP2pService(  894): InactiveState{ when=0 what=139268 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  894): setDetailed state send new extra info<unknown ssid>
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6669): 2015-12-19T00:32:24.642Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6669): 
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8970 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  894): connected time updated 588963
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  894): Unexpected BatchedScanResults :null
D/WifiScanningService(  894): SCAN_AVAILABLE : 1
D/RttService(  894): SCAN_AVAILABLE : 1
D/WifiScanningService(  894): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  894): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  894): [1,450,485,144,693 ms] noteScanEnd no scan source
D/WifiP2pService(  894): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): discovery change broadcast false
D/WifiP2pService(  894): P2pDisablingState
D/WifiP2pService(  894): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): p2p socket connection lost
D/WifiP2pService(  894): P2pDisabledState
,D/WifiP2pService(  894): P2pDisabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onWifiStateChanged: State changed to 1
E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): stop: Stopping services
E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService(  894): P2pDisabledState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): stop: Stopping P2P device discovery...
,D/WifiP2pService(  894): P2pDisabledState{ when=0 what=139268 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): DefaultState{ when=0 what=139268 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6669): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6669): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,I/jxcore-log( 6669): 2015-12-19T00:32:24.715Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6669): 
D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6669): onP2pDeviceListChanged: 0 device(s) discovered
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
D/WifiP2pService(  894): P2pDisabledState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/AndroidRuntime( 6669): Shutting down VM
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  894): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 8970): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8970): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8970): MmsConfig.loadMmsSettings
I/Babel_SMS( 8970): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8970): MmsConfig.loadFromDatabase
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/Tethering(  894): InitialState.processMessage what=4
,D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  0
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
,D/Tethering(  894): sendTetherStateChangedBroadcast 0, 0, 0
,E/Babel_SMS( 8970): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8970): MmsConfig.loadFromResources
E/Babel_SMS( 8970): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8970): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/        ( 2455): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,W/Settings( 8970): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8970): startup - clean
,I/Babel   ( 8970): deleted: false for 0
,W/VideoCapabilities( 8970): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8970): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8970): Unsupported mime video/mpeg2
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/VideoCapabilities( 8970): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8970): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8970): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8970): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8970): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8970): onServiceConnected
,W/Babel   ( 8970): Attempted to change video mute state without an active call.
D/TCMD    (  455): NL - Read 444 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 17
D/TCMD    (  455): Listening for incoming client connection request
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/TCMD    (  455): NL - Read 444 bytes from update socket.
,D/TCMD    (  455): NL - ignore NL message, type = 17
D/TCMD    (  455): Listening for incoming client connection request
,I/MDMCTBK (  306): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  306): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9016 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2590): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2590): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2590): [debug] > CusSM.onRadioDown
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1487): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2590): Registering with Alarm Manager to restart CCE
,I/MusicStore( 9016): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9016): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9016): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9016): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9016): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9016): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9016): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9016): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9016): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9016): GMSCore installation verified
,I/ConfigStore( 9016): Config Database version: 1
,I/art     (  894): Explicit concurrent mark sweep GC freed 35022(1975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.501ms total 122.284ms
,I/MediaRouter( 9016): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9016): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9064 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 25.192ms
,I/GHttpClientFactory( 9016): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9016): Using platform SSLCertificateSocketFactory
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 25.223ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.260ms
,I/ActivityManager(  894): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9083 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8489:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,V/Mms     ( 9064): mnc/mcc: 
V/Mms     ( 9064): tag: int value: recipientLimit - 20
,V/Mms     ( 9064): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9064): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9064): tag: int value: maxSubjectLength - 80
V/Mms     ( 9064): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9064): tag: bool value: enableGroupMms - false
V/Mms     ( 9064):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_8489/cgroup.procs: No such file or directory
,W/ResourcesManager( 9083): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9083): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 9064): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 9083): VM with version 2.1.0 has multidex support
I/MultiDex( 9083): install
I/MultiDex( 9083): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9107 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8685:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10055/pid_8685/cgroup.procs: No such file or directory
,V/JNIHelp ( 9083): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 9107): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9107): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9107): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ActivityThread( 9083): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9083): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ae0bb6e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9083): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  894): Killing 8417:com.android.settings/1000 (adj 15): empty #7
,D/NativeLibraryUtils( 9083): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_8417/cgroup.procs: No such file or directory
,I/iu.SyncManager( 9083): SYNC; picasa accounts
,D/NetworkLogImpl( 9083): Loaded NetworkSpeedPredictor
,I/ActivityManager(  894): Killing 8455:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_8455/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9138 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9159 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 8970): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  894): Killing 9016:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_9016/cgroup.procs: No such file or directory
,D/WifiP2pService(  894): P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/GAv4    ( 9159): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9159):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9159):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9159): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 9159): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9159): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9159): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 9159): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9159): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9159): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  0
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
,D/Tethering(  894): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  455): NL - Read 1008 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
,D/TCMD    (  455): Listening for incoming client connection request
,D/Tethering(  894): InitialState.processMessage what=4
,D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  0
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
D/Tethering(  894): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  455): NL - Read 1008 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/QsoftapCmd(  304): Got softap fwreload command we are passing on
,D/SoftapController(  304): Softap fwReload - Ok
,D/CommandListener(  304): Setting iface cfg
,D/CommandListener(  304): Trying to bring down wlan0
D/CommandListener(  304): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  894): setWifiState: enabling
E/WifiStateMachine(  894): Supplicant start successful
,D/WifiMonitor(  894): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WebViewFactory( 9159): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9159): Time to load native libraries: 2 ms (timestamps 6828-6830)
I/LibraryLoader( 9159): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9159): Binding Chromium to main looper Looper (main, tid 1) {3f42f0ca}
,I/LibraryLoader( 9159): Expected native library version number "",actual native library version number ""
,I/chromium( 9159): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9159): Initializing chromium process, singleProcess=true
,W/art     ( 9159): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9159): ApplicationContext is null in ApplicationStatus
,I/wpa_supplicant( 9218): Successfully initialized wpa_supplicant
I/wpa_supplicant( 9218): Long line in configuration file truncated
I/wpa_supplicant( 9218): rfkill: Cannot open RFKILL control device
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,W/chromium( 9159): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9159): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9159): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9159): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9159): Local Branch: 
I/Adreno-EGL( 9159): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9159): Local Patches: NONE
I/Adreno-EGL( 9159): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/libmdmdetect( 9218): ESOC framework not supported
E/Diag_Lib( 9218):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
E/wpa_supplicant( 9218): baseband property is set to [msm]
I/libmdmdetect( 9218): ESOC framework not supported
,E/wpa_supplicant( 9218):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9218): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9218): card_info[i].card_state: 0x0
E/wpa_supplicant( 9218): card_info[i].error_code: 0x0
E/wpa_supplicant( 9218): SIM/USIM not ready
E/wpa_supplicant( 9218): Error while reading SIM card status
,E/wpa_supplicant( 9218): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9218): card_info[i].card_state: 0x0
E/wpa_supplicant( 9218): card_info[i].error_code: 0x0
E/wpa_supplicant( 9218): SIM/USIM not ready
I/wpa_supplicant( 9218): eap_proxy: Card not ready
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,W/AudioManagerAndroid( 9159): Requires BLUETOOTH permission
,I/NSApplication( 9159): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9242 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9064:com.android.mms/u0a23 (adj 15): empty #7
,I/wpa_supplicant( 9218): Long line in configuration file truncated
I/wpa_supplicant( 9218): rfkill: Cannot open RFKILL control device
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,E/wpa_supplicant( 9218): baseband property is set to [msm]
I/libmdmdetect( 9218): ESOC framework not supported
,E/wpa_supplicant( 9218):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9218): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9218): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9218): card_info[i].error_code: 0x0
,E/wpa_supplicant( 9218): SIM/USIM not ready
E/wpa_supplicant( 9218): Error while reading SIM card status
,E/wpa_supplicant( 9218): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9218): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9218): card_info[i].error_code: 0x0
E/wpa_supplicant( 9218): SIM/USIM not ready
I/wpa_supplicant( 9218): eap_proxy: Card not ready
I/wpa_supplicant( 9218): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,E/WifiStateMachine(  894): Supplicant connection established
,E/WifiStateMachine(  894): setWifiState: enabled
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_9064/cgroup.procs: No such file or directory
,W/bt-btif ( 2455): dm_pm_timer expires
W/bt-btif ( 2455): dm_pm_timer expires 0
,W/bt-btif ( 2455): proc dm_pm_timer expires
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  894): Loading config and enabling all networks 
,E/WifiConfigStore(  894):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  894):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  894): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  894): Setting external_sim to 1
,W/Settings( 8970): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  894): Setting OUI to DA-A1-19
I/WifiNative-HAL(  894): startHal
E/wifi    (  894): getStaticLongField sWifiHalHandle 0xa2e0a89c
,D/wifi    (  894): halHandle = 0x0, mVM = 0xb7d2b310, mCls = 0x101686
I/WifiNative-HAL(  894): Could not start hal
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 9218): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  894): SCAN_AVAILABLE : 3
D/RttService(  894): SCAN_AVAILABLE : 3
D/WifiScanningService(  894): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  894): startHal
E/wifi    (  894): getStaticLongField sWifiHalHandle 0xa492b9cc
D/wifi    (  894): halHandle = 0x0, mVM = 0xb7d2b310, mCls = 0x15ee
I/WifiNative-HAL(  894): Could not start hal
E/WifiScanningService(  894): could not start HAL
,D/RttService(  894): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  304): Setting iface cfg
,D/CommandListener(  304): Trying to bring up p2p0
,D/WifiMonitor(  894): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  894): P2pEnablingState
D/WifiP2pService(  894): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2p socket connection successful
D/WifiP2pService(  894): P2pEnabledState
E/WifiStateMachine(  894): set country code US
D/WifiP2pService(  894): sending p2p connection changed broadcast
,E/WifiStateMachine(  894): set frequency band 2
,D/WifiNative-HAL(  894): p2pGetDeviceAddress
,D/WifiNative-HAL(  894): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,I/wpa_supplicant( 9218): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  894): DeviceAddress: 44:80:eb:7b:5a:07
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiP2pService(  894): MCC mode enabled 0
D/WifiP2pService(  894): mP2pAutoConnectSupport = 0
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiP2pService(  894): sending p2p persistent groups changed broadcast
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info0x
D/WifiP2pService(  894): InactiveState
D/WifiP2pService(  894): InactiveState{ when=-13ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-13ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): InactiveState{ when=-14ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-14ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9264 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 9107:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/MDMCTBK (  306): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  306): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): wifi_connect_to_supplicant, current pid is = 306
,D/MDMCTBK (  306): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  306): wifi_close_sockets: Exit
D/MDMCTBK (  306): wifi_ctrl_recv: Exiting
D/MDMCTBK (  306): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  306): wifi_close_sockets: Close Wifi socket
E/MDMCTBK (  306): Attach monitor thread
D/MDMCTBK (  306): wifi_close_sockets: Exit
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_9107/cgroup.procs: No such file or directory
,W/ResourcesManager( 9264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9287 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9307 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8970:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9287): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 9138:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_8970/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_9138/cgroup.procs: No such file or directory
,I/MusicStore( 9307): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9307): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9307): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9307): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9307): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9307): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9307): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9307): GMSCore installation verified
,I/ConfigStore( 9307): Config Database version: 1
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledStateupdate channel list
,I/MediaRouter( 9307): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9307): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  894): Explicit concurrent mark sweep GC freed 22825(1211KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.530ms total 114.099ms
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9354 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9307): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9307): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 9159:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,V/Mms     ( 9354): mnc/mcc: 
V/Mms     ( 9354): tag: int value: recipientLimit - 20
V/Mms     ( 9354): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9354): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9354): tag: int value: maxSubjectLength - 80
V/Mms     ( 9354): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9354): tag: bool value: enableGroupMms - false
V/Mms     ( 9354):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_9159/cgroup.procs: No such file or directory
,W/ResourcesManager( 9354): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9389 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9242:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_9242/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9389): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9389): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9389): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  894): Killing 9264:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_9264/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9408 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 23.303ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 21.816ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 19.753ms
,I/wpa_supplicant( 9218): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_306-4\x00 that cannot receive messages
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,E/WifiStateMachine(  894): [1,450,485,152,346 ms] noteScanEnd no scan source
,E/WifiStateMachine(  894): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f4fe31b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  894): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  894):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  894): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  894): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  894): will read network variables netId=0
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9432 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  894): Killing 9287:android.process.acore/u0a7 (adj 15): empty #7
,E/WifiStateMachine(  894): CMD_AUTO_CONNECT did save config ->  nid=0
W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_9287/cgroup.procs: No such file or directory
E/WifiConfigStore(  894): will read network variables netId=0
,I/wpa_supplicant( 9218): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 9218): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  894): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiConfigStore(  894): setLastSelectedConfiguration -1
,E/wpa_supplicant( 9218): PNO: In assoc process
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 9432): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  455): NL - Read 312 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 192 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 9218): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  0
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  894): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 9218): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 9218): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
,D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): Network connection established
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  894): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  894): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  894): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  894): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  894): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  304): Setting iface cfg
E/WifiStateMachine(  894): Start Dhcp Watchdog 3
E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend false
,E/wpa_supplicant( 9218): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  894): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 9218): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@181ccb76 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@181ccb76 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 9432): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9432): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9432): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9432): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9432): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9432): MmsConfig.loadFromResources
,E/Babel_SMS( 9432): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9432): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9432): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9432): startup - clean
,I/Babel   ( 9432): deleted: false for 0
,E/DHCPCD  ( 9465): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9465): version 5.5.6 starting
,E/DHCPCD  ( 9465): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9465): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9465): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9471 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DHCPCD  ( 9465): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 9465): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 9465): wlan0: sending REQUEST (xid 0x8d8d4506), next in 4.37 seconds
,W/VideoCapabilities( 9432): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9432): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9432): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9432): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9432): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9432): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9432): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9432): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9432): onServiceConnected
W/Babel   ( 9432): Attempted to change video mute state without an active call.
,I/Babel   ( 9432): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  894): Killing 9307:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_9307/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9471): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9471):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9471):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9471): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9471): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9471): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9471): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9471): Time to load native libraries: 1 ms (timestamps 217-218)
I/LibraryLoader( 9471): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9471): Binding Chromium to main looper Looper (main, tid 1) {3f42f0ca}
,I/LibraryLoader( 9471): Expected native library version number "",actual native library version number ""
,I/chromium( 9471): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9471): Initializing chromium process, singleProcess=true
,W/art     ( 9471): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9471): ApplicationContext is null in ApplicationStatus
,W/chromium( 9471): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9471): Local Branch: 
I/Adreno-EGL( 9471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9471): Local Patches: NONE
I/Adreno-EGL( 9471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9471): Requires BLUETOOTH permission
,I/NSApplication( 9471): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9544 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 9354:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_9354/cgroup.procs: No such file or directory
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9572 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9389:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_9389/cgroup.procs: No such file or directory
,W/ResourcesManager( 9572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9599 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9432:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9599): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/DHCPCD  ( 9465): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9465): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9465): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/DHCPCD  ( 9465): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  455): NL - ignore NL message, type = 20
D/TCMD    (  455): Listening for incoming client connection request
D/DHCPCD  ( 9465): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9465): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9465): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager(  894): Killing 9408:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2590): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_9432/cgroup.procs: No such file or directory
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  894): send {38d61554, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_9408/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2590): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2590): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2590): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2590): onServiceConnected()
D/GetNotificationsWS( 2590): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2590): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1747): callingUid 10016, callindPid: 1747
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [144ms]
,E/MDM     ( 1747): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 9083): Restart initialization of location
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 9083): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9083): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9661 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  894): WifiStateMachine DHCP successful
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  894): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  894): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,E/WifiStateMachine(  894): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService(  894): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  894):    accepting network in place of null
,D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
,I/art     (  894): Explicit concurrent mark sweep GC freed 31965(1573KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.603ms total 120.628ms
,W/IcingInternalCorpora( 9083): getNumBytesRead when not calculated.
,V/AlarmManager(  894): done {38d61554, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [636ms]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 19 Dec 2015 00:32:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450485155757], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450485155641]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1548): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1548): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9715 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 9715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9715): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9715): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9715): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9715): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9715): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9715): MmsConfig.loadFromResources
,E/Babel_SMS( 9715): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9715): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9715): startup - clean
,I/Babel   ( 9715): deleted: false for 0
,W/VideoCapabilities( 9715): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9715): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9715): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9715): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9715): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9715): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9715): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  894): Killing 9471:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_9471/cgroup.procs: No such file or directory
,I/vclib   ( 9715): onServiceConnected
,W/Babel   ( 9715): Attempted to change video mute state without an active call.
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1487): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 674451 ,futureTime: 9223372036854775807
,D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 674455 ,futureTime: 9223372036854775807
D/PollingManager( 2590): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2590): now: 674455 ,futureTime: 9223372036854775807
D/OtaApp  ( 2590): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9759 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Central_PollingManager( 1487): now: 674505 ,futureTime: 86475457
D/Central_PollingManager( 1487): Polling alarm set to expire at: 86475457 Current Time: 674505
,D/OtaApp  ( 2590): [debug] > PollingManagerService, now: 674508 ,futureTime: 38962129
,D/OtaApp  ( 2590): [debug] > Polling alarm set to expire at: 38962129 Current Time: 674510
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2590): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2590): set mOutstandingReq to true.
,I/ Nonce  ( 2590):  Nonce getNonce 
I/ Nonce  ( 2590):  Nonce Request 
I/ Nonce  ( 2590):  Nonce execute Request 
,D/MMApiWebService( 2590): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2590): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2590): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2590): createDeviceIdOrLogin update_device
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2590): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2590): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2590): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2590): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2590): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2590): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2590): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MusicStore( 9759): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9759): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 2590): Explicit concurrent mark sweep GC freed 44829(2MB) AllocSpace objects, 8(151KB) LOS objects, 40% free, 11MB/19MB, paused 1.304ms total 85.229ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9759): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9759): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 6046(300KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 1.218ms total 29.601ms
,D/MMApiWebService( 2590): generating token using payload instead of using session token
,D/ Nonce  ( 2590):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2590): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 9759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9759): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9759): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cd479a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9759): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9759): GMSCore installation verified
,I/ConfigStore( 9759): Config Database version: 1
,I/MediaRouter( 9759): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9759): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9759): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9808 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/GHttpClientFactory( 9759): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9759): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 9544:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_9544/cgroup.procs: No such file or directory
,V/Mms     ( 9808): mnc/mcc: 
V/Mms     ( 9808): tag: int value: recipientLimit - 20
V/Mms     ( 9808): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9808): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9808): tag: int value: maxSubjectLength - 80
V/Mms     ( 9808): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9808): tag: bool value: enableGroupMms - false
V/Mms     ( 9808):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  894): Explicit concurrent mark sweep GC freed 9998(455KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.500ms total 118.184ms
,W/ResourcesManager( 9808): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9834 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9572:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_9572/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9834): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9834): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9834): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  894): Killing 9599:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_9599/cgroup.procs: No such file or directory
,I/art     ( 5687): Explicit concurrent mark sweep GC freed 1536(53KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 876us total 23.312ms
,I/CheckinService( 9083): Checkin interval check for package: unspecified last checkin: 1450484733864 min interval config: 0 actual interval: 424994
,I/CheckinService( 9083): Disabling old GoogleServicesFramework version
,I/iu.Environment( 9083): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 9083): num queued entries: 0
,I/iu.UploadsManager( 9083): num updated entries: 0
I/iu.SyncManager( 9083): NEXT; no task
,I/CheckinService( 9083): Checking schedule, now: 1450485158895 next: 1450484763846
I/CheckinService( 9083): active receiver: enabled
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10016
,I/CheckinService( 9083): Preparing to send checkin request
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
,I/EventLogService( 9083): Accumulating logs since 1450484729914
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9859 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.058ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 19 Dec 2015 00:32:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450485158978], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450485158919]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 19.967ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.140ms
,I/Babel   ( 9715): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9859): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 9859): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9859):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9859):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9859): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9859): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9859): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 9083): Checkin reason type: 8 attempt count: 1
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9859): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/WifiService(  894): New client listening to asynchronous messages
,E/ActivityThread( 9083): Failed to find provider info for com.google.android.wearable.settings
,W/GAv4    ( 9859): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ Nonce  ( 2590):  Nonce Reponse 
D/        ( 2590): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"9fcb4540-23ba-493d-95a6-643814f04bab"}
,D/MMApiWSBase( 2590): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2590):  Nonce Handle Reponse 
D/MMApiProvisionService( 2590): mOutstandingReq set to false
,W/GAv4    ( 9859): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiProvisionService( 2590):  pTime 1450461116267 sExp 172742 cTime 1450485159246 tTime 1450633858267
D/MMApiProvisionService( 2590):  No login Required 
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  894): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9908 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WebViewFactory( 9859): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/MultiDex( 9908): VM with version 2.1.0 has multidex support
,I/MultiDex( 9908): install
,I/MultiDex( 9908): VM has multidex support, MultiDex support library is disabled.
,I/LibraryLoader( 9859): Time to load native libraries: 2 ms (timestamps 6139-6141)
I/LibraryLoader( 9859): Expected native library version number "",actual native library version number ""
V/JNIHelp ( 9908): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/WebViewChromiumFactoryProvider( 9859): Binding Chromium to main looper Looper (main, tid 1) {3efe5d58}
,I/LibraryLoader( 9859): Expected native library version number "",actual native library version number ""
I/chromium( 9859): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9859): Initializing chromium process, singleProcess=true
,W/art     ( 9859): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9859): ApplicationContext is null in ApplicationStatus
,W/chromium( 9859): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9859): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9859): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9859): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9859): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9859): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9859): Local Branch: 
I/Adreno-EGL( 9859): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9859): Local Patches: NONE
I/Adreno-EGL( 9859): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityThread( 9908): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9908): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37c1a28: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9908): Installed default security provider GmsCore_OpenSSL
,I/art     ( 9908): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 9908): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/AudioManagerAndroid( 9859): Requires BLUETOOTH permission
,I/NSApplication( 9859): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9947 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 9759:com.google.android.music:main/u0a80 (adj 15): empty #7
D/NativeLibraryUtils( 9908): Install completed successfully. count=14 extracted=0
,W/DataUsage( 2590): invalid counter update blocked: 'err' by 0
D/Checkin ( 2590): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_9759/cgroup.procs: No such file or directory
,D/WVCdm   (  309): Instantiating CDM.
,I/WVCdm   (  309): CdmEngine::OpenSession
,I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5500960
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb8179af0, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9967 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8194ca8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  894): Killing 9808:com.android.mms/u0a23 (adj 15): empty #7
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa830, idLength=0xbeaad2b0
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=2646591802
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb82a0858
D/DrmWidevineDash(  309): message_length=1591, signature=0xb82a60d8, signature_length=3198866068
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_9808/cgroup.procs: No such file or directory
,W/ResourcesManager( 9967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9992 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 9661:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 9992): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 9834:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,E/MDMCTBK (  306): Unable to attach monitor connection to supplicant on @android:wpa_wlan0
,D/MDMCTBK (  306): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  306): wifi_close_sockets: Exit
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_9661/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2590): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_9834/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2590): bindWebServices(): registering our AIDL callback...
I/SundryService( 2590): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2590): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2590): onServiceConnected()
D/GetNotificationsWS( 2590): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2590): started with background data enabled, making sure notification mechanism is enabled
D/GetNotificationsWS( 2590): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2590): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2590): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2590): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  894): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1487): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/dex2oat (10017): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=10018 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2590): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2590): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2590): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2590): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2590): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2590): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,I/dex2oat (10017): dex2oat took 99.336ms (threads: 4)
,I/Adreno-EGL( 9908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9908): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9908): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9908): Local Branch: 
I/Adreno-EGL( 9908): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9908): Local Patches: NONE
I/Adreno-EGL( 9908): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9908): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9908): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9908): Local Branch: 
I/Adreno-EGL( 9908): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9908): Local Patches: NONE
I/Adreno-EGL( 9908): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  309): CdmEngine::OpenSession
I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/WearableService( 1747): callingUid 10016, callindPid: 1747
,E/MDM     ( 1747): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 9083): Restart initialization of location
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5025000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb5500960
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb8179ce0, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8194ca8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb82aa870, idLength=0xb1416730
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=3231194505
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb817a380
D/DrmWidevineDash(  309): message_length=1626, signature=0xb82a60d8, signature_length=2973853460
,I/art     (  894): Explicit concurrent mark sweep GC freed 12310(601KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.551ms total 136.402ms,
,I/ActivityManager(  894): Killing 9859:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_9859/cgroup.procs: No such file or directory
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
,I/Adreno-EGL( 9908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9908): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9908): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9908): Local Branch: 
I/Adreno-EGL( 9908): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9908): Local Patches: NONE
I/Adreno-EGL( 9908): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9908): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9908): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9908): Local Branch: 
I/Adreno-EGL( 9908): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9908): Local Patches: NONE
I/Adreno-EGL( 9908): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 9083): Classify the device as Phone.
,I/CheckinTask( 9083): Sending checkin request (9673 bytes)
,I/CheckinRequestBuilder( 9083): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9083): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 9083): Classify the device as Phone.
,I/CheckinTask( 9083): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9083): Checking schedule, now: 1450485162468 next: 1451086299444
I/CheckinService( 9083): active receiver: disabled
,D/CheckinService( 9083): Recording last checkin time for package unspecified as 1450485162496
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=10076 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor(10076): Register our PhoneStateListener
,V/SetupWizard(10076): Connected to Gservices successfully
,I/ActivityManager(  894): Killing 9947:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_9947/cgroup.procs: No such file or directory
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/bt-btif ( 2455): invalid rfc slot id: 27
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 897, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6669): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 895
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 897
D/io.jxcore.node.IncomingSocketThread( 6669): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6669): doStop: Thread ID: 896
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6669): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6669): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 897, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6669): Either failed to read from the output stream or write to the input stream (thread ID: 896, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6669): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6669): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6669): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6669): Exiting thread (ID: 896, name: Sender)
,I/ActivityManager(  894): Killing 9992:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  894): Killing 9967:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_9992/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_9967/cgroup.procs: No such file or directory
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311371, SEQNUM=4690, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-1800, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  306): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=10104 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38125d89:true
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=1
,W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2455): new conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2455): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6669): Incoming connection accepted
,W/google-breakpad(10138): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad(10138): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad(10138): S 0 A1ACBFF0 A1ACB000 00008000
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10147 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/google-breakpad(10138): S A1ACB000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10138): S A1ACB180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad(10138): S A1ACB300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad(10138): S A1ACB480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad(10138): S A1ACB600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10138): S A1ACB780 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B099F4B7000000009A270000A099F4B7B099F4B7000000000010000000B0A5B400000000000000000D1A0000B099F4B7A099F4B7C0B8ACA17003000000000000C0B8ACA1E42DF6B6A099F4B780BCACA100BDACA1A8947EA99B782DA90B0000000000000002000000F09FACA1000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad(10138): S A1ACB900 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AE2000000000000000000000000000000000B8A400000000002000000E00000017000000041200006871406FE0A5E76F901A292300AF4C23C40000006871406FE0A5E76F00AF4C2338A6E76F700886B9901A292370B8BCA1F09FACA1F0BFACA16D2AB2713C2AB27130000FA0F09FACA1041200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000AE20000000000000D0FFFFFF00001582983A0000000000000A510600000010820000000000000000
,W/google-breakpad(10138): S A1ACBA80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E404428231026282310BA2923000000000000000000B53C6F0000000000742A2358CD9F73100000006C0000000D1A000000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF130000600000000000000040A0C7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad(10138): S A1ACBC00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000027438633000000000B00000080BCACA100BDACA10000000053792DA9089BF1A00000000004000040F09926B86871406FC40000006871406FE0A5E76F00AF4C2338A6E76F700886B98033F7B60B0000000000000002000000F09FACA10000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B8A400000000002000000E00000017000000041200006871406FE0A5E76F901A292300AF4C23C40000006871406FE0A5E76F00AF4C2338A6E76F700886B9901A292370B8BCA1F09FACA1F0BFACA16D2AB2713C2AB27130000FA0F09FACA1041200000000000000000000000000000000000000000000
W/google-breakpad(10138): S A1ACBD80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000AE20000000000000D0FFFFFF00001582983A0000000000000A51060000001082000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E404428231026282310BA2923000000000000000000B53C6F0000000000742A2358CD9F73100000006C0000000D1A000000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF130000600000000000000040A0C7FBC0
W/google-breakpad(10138): S A1ACBF00 3465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACC980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
I/BluetoothClassifier(10104): Bluetooth Device Name: Thali Test (Galaxy A3)
W/google-breakpad(10138): S A1ACCB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACCC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACCE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACCF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACD880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACDA00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACDB80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACDD00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACDE80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACE900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACEA80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271,
W/google-breakpad(10138): S A1ACEC00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACED80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACEF00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACF980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACFB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACFC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACFE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1ACFF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD0E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
I/ActivityManager(  894): Killing 10076:com.google.android.setupwizard/u0a35 (adj 15): empty #7
W/google-breakpad(10138): S A1AD1780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD1F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F,00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB271
W/google-breakpad(10138): S A1AD2F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F00AF4C2338A6E76F901A29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F00AF4C23E0A5E76F901A2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad(10138): C 060000406871406FE0A5E76F901A292300AF4C23C40000006871406FE0A5E76F00AF4C2338A6E76F700886B9901A292370B8BCA1F09FACA1F0BFACA16D2AB2713C2AB27130000FA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10138): M B6F84000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad(10138): M A0BB3000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad(10138): M A44E0000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad(10138): M A44EA000 00000000 00009000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad(10138): M A4805000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad(10138): M A5AA7000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad(10138): M A6AD0000 00000000 00006000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
W/google-breakpad(10138): M A726F000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
,W/google-breakpad(10138): M A7B8F000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad(10138): M ADF8F000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad(10138): M ADF92000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
W/google-breakpad(10138): M ADFA2000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
W/google-breakpad(10138): M AE0DD000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad(10138): M AE111000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad(10138): M AE139000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad(10138): M AE700000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad(10138): M AE718000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad(10138): M AE721000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad(10138): M AE727000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad(10138): M AE72B000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
W/google-breakpad(10138): M AE739000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
W/google-breakpad(10138): M AE754000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
W/google-breakpad(10138): M AE758000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
W/google-breakpad(10138): M AE777000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad(10138): M AE77A000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
W/google-breakpad(10138): M AE781000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
W/google-breakpad(10138): M AE786000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
W/google-breakpad(10138): M AE7C2000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
W/google-breakpad(10138): M AE7DD000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
,W/google-breakpad(10138): M AE904000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
,W/google-breakpad(10138): M AE91B000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad(10138): M AE947000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad(10138): M B0DA9000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
,W/google-breakpad(10138): M B24AF000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad(10138): M B2524000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad(10138): M B2545000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
,W/google-breakpad(10138): M B2548000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
,W/google-breakpad(10138): M B2550000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
,W/google-breakpad(10138): M B4440000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad(10138): M B4E4B000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad(10138): M B4E55000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
W/google-breakpad(10138): M B5187000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad(10138): M B518B000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
W/google-breakpad(10138): M B51CC000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
,W/google-breakpad(10138): M B52CB000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
W/google-breakpad(10138): M B52DA000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
W/google-breakpad(10138): M B52E9000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,I/ActivityManager(  894): Killing 10018:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/google-breakpad(10138): M B52ED000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
,W/google-breakpad(10138): M B574D000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
W/google-breakpad(10138): M B5751000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad(10138): M B5758000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
W/google-breakpad(10138): M B575C000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
,W/google-breakpad(10138): M B5768000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
,W/google-breakpad(10138): M B576B000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad(10138): M B5780000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad(10138): M B57D6000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad(10138): M B57E5000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad(10138): M B57EF000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad(10138): M B588A000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad(10138): M B58C7000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
,W/google-breakpad(10138): M B58E2000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad(10138): M B58EF000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad(10138): M B5922000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
W/google-breakpad(10138): M B5B58000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
W/google-breakpad(10138): M B5B75000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad(10138): M B5B9D000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
,W/google-breakpad(10138): M B5BF7000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
W/google-breakpad(10138): M B5C34000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad(10138): M B5C77000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
W/google-breakpad(10138): M B5D0D000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
W/google-breakpad(10138): M B664C000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad(10138): M B6686000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
,W/google-breakpad(10138): M B66D2000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
,W/google-breakpad(10138): M B67E6000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/google-breakpad(10138): M B67EC000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=0
,W/bt-btif ( 2455): bta_dm_check_av:0
W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,W/google-breakpad(10138): M B6953000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad(10138): M B699B000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
,W/google-breakpad(10138): M B69A0000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
W/google-breakpad(10138): M B69A7000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad(10138): M B69AF000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
,W/google-breakpad(10138): M B69C6000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
W/google-breakpad(10138): M B6B27000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
,W/google-breakpad(10138): M B6B2A000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
,W/google-breakpad(10138): M B6B36000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
,W/google-breakpad(10138): M B6B39000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
,W/google-breakpad(10138): M B6B88000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad(10138): M B6B90000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
,W/google-breakpad(10138): M B6BCA000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
,W/google-breakpad(10138): M B6BD0000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad(10138): M B6BD6000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
,W/google-breakpad(10138): M B6BF0000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
,W/google-breakpad(10138): M B6C20000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
,W/google-breakpad(10138): M B6C48000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
,W/google-breakpad(10138): M B6C53000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
,W/google-breakpad(10138): M B6C5A000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
W/google-breakpad(10138): M B6C5E000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
,W/google-breakpad(10138): M B6C62000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad(10138): M B6CB6000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
W/google-breakpad(10138): M B6CBF000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad(10138): M B6CC8000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad(10138): M B6CE0000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
,W/google-breakpad(10138): M B6D1B000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad(10138): M B6D29000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad(10138): M B6D9A000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad(10138): M B6E05000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
W/google-breakpad(10138): M B6EE2000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
W/google-breakpad(10138): M B6EE6000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
,W/google-breakpad(10138): M B6F00000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
,W/google-breakpad(10138): M B6F08000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
W/google-breakpad(10138): M B6F6C000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_10018/cgroup.procs: No such file or directory
W/google-breakpad(10138): M B6F74000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
,W/google-breakpad(10138): -----END BREAKPAD MICRODUMP-----
W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_10076/cgroup.procs: No such file or directory
,W/google-breakpad( 6669): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 6669): Chrome build fingerprint:
,W/google-breakpad( 6669): 0.0.1
,W/google-breakpad( 6669): 18
W/google-breakpad( 6669): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6669): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 6669): ### WebView Version 44.0.2403.90 (code 240309000)
F/libc    ( 6669): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa1ac9ff0 in tid 8366 (Thread-798)
,I/DEBUG   (  305): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   (  305): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
I/DEBUG   (  305): Revision: 'p300'
I/DEBUG   (  305): ABI: 'arm'
I/DEBUG   (  305): pid: 6669, tid: 8366, name: Thread-798  >>> com.test.thalitest <<<
I/DEBUG   (  305): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa1ac9ff0
,I/DEBUG   (  305):     r0 6f407168  r1 6fe7a5e0  r2 23291a90  r3 234caf00
,I/DEBUG   (  305):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 234caf00
I/DEBUG   (  305):     r8 6fe7a638  r9 b9860870  sl 23291a90  fp a1bcb870
I/DEBUG   (  305):     ip a1ac9ff0  sp a1acbff0  lr 71b22a6d  pc 71b22a3c  cpsr a00f0030
I/DEBUG   (  305): 
I/DEBUG   (  305): backtrace:
I/DEBUG   (  305):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   (  305):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f3769c rs_disc_pending=1
W/bt-btif ( 2455): bta_dm_check_av:0
,W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  894): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10189 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/DEBUG   (  305): 
I/DEBUG   (  305): Tombstone written to: /data/tombstones/tombstone_06
,I/BootReceiver(  894): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  894): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  894): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 9715): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9715): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/BackupManagerService(  894): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@25140a81
,I/WindowState(  894): WIN DEATH: Window{26e0528d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  894): Client connection lost with reason: 4
,V/JNIHelp ( 9715): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 9715): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9715): Installed default security provider GmsCore_OpenSSL
,I/ContactLocale(10189): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  894): failed to kill 1 processes for processgroup 6669
,I/ActivityManager(  894): Process com.test.thalitest (pid 6669) has died
,I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Zygote  (  323): Process 6669 exited due to signal (11)
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10217 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/Launcher( 1583): Deferring update until onResume
,W/asset   (10217): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10217): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager(10217): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10217): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(10104): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@37ca1529 new=com.google.android.velvet.VelvetApplication@37ca1529
,D/PackageBroadcastService( 9083): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10241 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 9083): Null package name or gms related package.  Ignoreing.
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.273ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.745ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.661ms
,W/ResourcesManager(10241): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(10104): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=1
W/bt-btif ( 2455): bta_dm_check_av:0
W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,I/Icing   ( 9083): Storage manager: low false usage 1.79MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  894): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10275 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 9083): updateResources: need to parse f{com.google.android.gms}
,I/art     (  894): Explicit concurrent mark sweep GC freed 17677(1029KB) AllocSpace objects, 9(3MB) LOS objects, 33% free, 20MB/30MB, paused 1.472ms total 120.691ms
,I/ActivityManager(  894): Killing 9908:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/SQLiteConnectionPool( 9083): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_9908/cgroup.procs: No such file or directory
,I/Icing   ( 9083): Internal init done: storage state 0
,I/Icing   ( 9083): Post-init done
,I/Icing   ( 9083): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:32000 mC
,D/Finsky  (10275): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): tBTM_SEC_DEV:0xa6f36ddc rs_disc_pending=0
W/bt-btif ( 2455): bta_dm_check_av:0
W/bt-btif ( 2455): btif_dm_cback : unhandled event (14)
,D/Finsky  (10275): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10275): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10275): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/bt-btif ( 2455): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
E/bt-btif ( 2455): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,D/Finsky  (10275): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  (10275): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     (10275): Skipping gmscore version check
,I/ActivityManager(  894): Killing 10147:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_10147/cgroup.procs: No such file or directory
,D/Finsky  (10275): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10275): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 9083): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9083): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 9083): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  894): Killing 10217:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10027/pid_10217/cgroup.procs: No such file or directory
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/ActivityManager(  894): Killing 9715:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_9715/cgroup.procs: No such file or directory
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  306): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  306): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  306): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  306): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
,I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2455): dm_pm_timer expires
,W/bt-btif ( 2455): dm_pm_timer expires 0
,W/bt-btif ( 2455): proc dm_pm_timer expires
,I/CheckinService( 9083): Done disabling old GoogleServicesFramework version
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 2455): bta_dm_pm_btm_status  hci_status=22
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  306): , Wifi = 0
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  306): , Wifi = 0
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully,
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311472, SEQNUM=4706, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-1912, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2455): info:x10
,D/        ( 2455): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2455): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2455): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2455): onReceive
,I/BTConnectionReceiver(10104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10104): Bluetooth Device Name: HTC One M8s
,I/art     ( 2455): Explicit concurrent mark sweep GC freed 63615(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/13MB, paused 1.065ms total 59.646ms
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {167f2a0e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  894): send {2643454b, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  894): done {167f2a0e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [46ms]
,V/AlarmManager(  894): done {2643454b, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [55ms]
,I/EventLogService( 9083): Aggregate from 1450485159072 (log), 1450483290197 (data)
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311650, SEQNUM=4712, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-2173, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311026, SEQNUM=4714, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-2428, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  894): User[0] Flushing usage stats to disk
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {45a31d4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  894): cleanup(): cleared. Last call was 731106 ms ago
I/ActivityManager(  894): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=10369 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [96ms]
,I/GAv4    (10369): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (10369):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10369):   adb logcat -s GAv4
,W/GAv4    (10369): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10369): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10369): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  894): done {45a31d4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [202ms]
I/ActivityManager(  894): Killing 10189:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_10189/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  894): send {338dff7d, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [46ms]
,V/AlarmManager(  894): done {338dff7d, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [91ms]
,V/AlarmManager(  894): send {167f2a0e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  894): done {167f2a0e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,I/GoogleURLConnFactory( 1747): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1747): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,W/PhenotypeConfigurator( 1747): IOException while sending for: 
W/PhenotypeConfigurator( 1747): java.net.SocketTimeoutException: SSL handshake timed out
W/PhenotypeConfigurator( 1747): 	at com.android.org.conscrypt.NativeCrypto.SSL_do_handshake(Native Method)
W/PhenotypeConfigurator( 1747): 	at com.android.org.conscrypt.OpenSSLSocketImpl.startHandshake(OpenSSLSocketImpl.java:302)
W/PhenotypeConfigurator( 1747): 	at android.net.SSLCertificateSocketFactory.verifyHostname(SSLCertificateSocketFactory.java:190)
W/PhenotypeConfigurator( 1747): 	at android.net.SSLCertificateSocketFactory.createSocket(SSLCertificateSocketFactory.java:435)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.Connection.upgradeToTls(Connection.java:171)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.Connection.connect(Connection.java:151)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
W/PhenotypeConfigurator( 1747): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:948)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:766)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:674)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:658)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:1353)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:799)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:753)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.c(SourceFile:475)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:438)
W/PhenotypeConfigurator( 1747): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311235, SEQNUM=4723, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-540, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311235, SEQNUM=4724, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-541, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311516, SEQNUM=4725, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-637, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
,I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  894): send {23c67665, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {7e67362, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  894): send {38e2ec17, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  894): Prepared write state in 15ms
,I/ProcessStatsService(  894): Prepared write state in 6ms
,V/AlarmManager(  894): done {7e67362, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [68ms]
,V/AlarmManager(  894): done {23c67665, *alarm*:android.intent.action.TIME_TICK} [82ms]
,V/AlarmManager(  894): done {38e2ec17, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [96ms]
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  894): Pruning old procstats: /data/system/procstats/state-2015-12-18-13-01-44.bin
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(10457): 
D/AndroidRuntime(10457): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10457): CheckJNI is OFF
D/AndroidRuntime(10457): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10393 user=-1: uninstall pkg
I/ActivityManager(  894):   Force finishing activity ActivityRecord{62d3d2e u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  894): Skipping PackageSetting{2bde1efc com.example.hello/10377} due to missing metadata
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10393 user=0: pkg removed
I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  894): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10476 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 3019): Explicit concurrent mark sweep GC freed 21725(3MB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 7MB/12MB, paused 947us total 83.909ms
I/Keyboard.Facilitator( 1431): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1431): run()
I/Decoder ( 1431): createOrResetDecoder
I/ConfigService( 1747): onCreate
I/art     ( 1583): Explicit concurrent mark sweep GC freed 5387(327KB) AllocSpace objects, 7(353KB) LOS objects, 25% free, 13MB/17MB, paused 2.111ms total 103.147ms
D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1431): run()
D/TaskPersister(  894): removeObsoleteFile: deleting file=3_task.xml
D/VoicemailCleanupService(10476): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1431): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1431): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1431): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1431): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1431): run()
I/StatsUtilsManager( 1431): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1431): shouldRecordStats() = Too Soon
I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10508 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale(10476): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  894): Killing 10241:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  894): Explicit concurrent mark sweep GC freed 33179(1995KB) AllocSpace objects, 11(265KB) LOS objects, 33% free, 20MB/31MB, paused 1.850ms total 234.517ms
I/art     (  894): WaitForGcToComplete blocked for 142.638ms for cause Explicit
I/Launcher( 1583): Deferring update until onResume
W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_10241/cgroup.procs: No such file or directory
D/AndroidRuntime(10457): Shutting down VM
W/asset   (10508): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10508): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10508): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  894): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10529 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  894): Explicit concurrent mark sweep GC freed 5667(358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.720ms total 192.364ms
I/ActivityManager(  894): Killing 10275:com.android.vending/u0a32 (adj 15): empty #7
W/ContextImpl(10529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_10275/cgroup.procs: No such file or directory
D/PackageBroadcastService( 9083): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 9083): Reading stored module config
D/AccountUtils( 9083): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 9083): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9083): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 9083): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 9083): App measurement is starting up, version: 8489
I/GMPM-SVC( 9083): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 1747): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1747): Shutting down VM
E/AndroidRuntime( 1747): FATAL EXCEPTION: main
E/AndroidRuntime( 1747): Process: com.google.android.gms.persistent, PID: 1747
E/AndroidRuntime( 1747): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1747): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1747): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1747): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1747): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1747): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1747): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1747): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1747): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1747): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1747): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1747): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1747): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1747): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1747): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1747): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1747): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1747): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1747): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1747): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1747): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1747): 	... 9 more
I/Process ( 1747): Sending signal. PID: 1747 SIG: 9
E/DropBoxManagerService(  894): Can't write: system_app_crash
E/DropBoxManagerService(  894): java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  894): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  894): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  894): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  894): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  894): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  894): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  894): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  894): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  894): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  894): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  894): 	... 5 more
I/Icing   ( 9083): doRemovePackageData com.test.thalitest
D/GpsStatusListenerHelper(  894): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@1beb34b5
D/WifiService(  894): Client connection lost with reason: 4
V/BackupManagerService(  894): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
E/SQLiteDatabase( 9083): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 9083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 9083): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 9083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 9083): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 9083): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 9083): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 9083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 9083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 9083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 9083): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 9083): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 9083): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 9083): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 9083): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 9083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 9083): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 9083): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 9083): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 9083): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 9083): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 9083): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 9083): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/FileUtils( 9083): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/AndroidRuntime( 9083): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 9083): Process: com.google.android.gms, PID: 9083
E/AndroidRuntime( 9083): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 9083): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 9083): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 9083): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 9083): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 9083): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 9083): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 9083): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 9083): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 9083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 9083): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 9083): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing   ( 9083): Failed to open Apps corpus file.
E/SQLiteDatabase( 9083): Failed to open database '/data/data/com.google.android.gms/databases/pluscontacts.db'.
E/SQLiteDatabase( 9083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9083): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.c.f.d(SourceFile:2487)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.c.f.b(SourceFile:787)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 9083): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 9083): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 9083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 9083): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 9083): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 9083): Sending signal. PID: 9083 SIG: 9
D/WifiService(  894): Client connection lost with reason: 4
I/ActivityManager(  894): Process com.google.android.gms.persistent (pid 1747) has died
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 1000ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService in 10998ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 20996ms
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 40995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 50995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 60995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 70995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 80995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 90995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 100995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 110995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 120995ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 130995ms

```
