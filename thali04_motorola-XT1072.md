#### Test 549702617cfd775_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6532): 
D/AndroidRuntime( 6532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6532): CheckJNI is OFF
D/AndroidRuntime( 6532): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6551 uid=10435 gids={50435, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6532): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6551): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6551): Time to load native libraries: 19 ms (timestamps 7339-7358)
I/LibraryLoader( 6551): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6551): Binding Chromium to main looper Looper (main, tid 1) {32685527}
I/LibraryLoader( 6551): Expected native library version number "",actual native library version number ""
I/chromium( 6551): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6551): Initializing chromium process, singleProcess=true
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6551): ApplicationContext is null in ApplicationStatus
W/chromium( 6551): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6551): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6551): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6551): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6551): Local Branch: 
I/Adreno-EGL( 6551): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6551): Local Patches: NONE
I/Adreno-EGL( 6551): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ActivityManager(  885): Activity pause timeout for ActivityRecord{3b5d3716 u0 com.test.thalitest/.MainActivity t3}
D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21fa5225:true
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6551): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6551): CordovaWebView is running on device made by: motorola
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6551): Render dirty regions requested: true
D/Atlas   ( 6551): Validating map...
W/chromium( 6551): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6551): Initialized EGL, version 1.4
D/OpenGLRenderer( 6551): Enabling debug mode 0
I/Keyboard.Facilitator( 1421): onFinishInput()
I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1034
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +961ms (total +1s34ms)
W/IInputConnectionWrapper( 6551): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6551): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 6551): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6551): Cannot call determinedVisibility() - never saw a connection for the pid: 6551
,D/JsMessageQueue( 6551): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6551): JniHelper::setJavaVM(0xb71a2310), pthread_self() = -1219288376
D/JX-Cordova( 6551): jxcore cordova android initializing
,W/jxcore-log( 6551): Initializing JXcore engine
W/jxcore-log( 6551): JXcore engine is ready
,W/jxcore-log( 6551): Starting JXcore engine
,W/.test.thalitest( 6551): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10435 path="socket:[8368]" dev="sockfs" ino=8368 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6551): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10435 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6551): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10435 path="socket:[6577]" dev="sockfs" ino=6577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6551): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10435 path="socket:[28936]" dev="sockfs" ino=28936 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6551): Platform android
W/jxcore-log( 6551): 
,W/jxcore-log( 6551): Process ARCH arm
W/jxcore-log( 6551): 
,I/jxcore-log( 6551): JXcore Cordova bridge is ready!
I/jxcore-log( 6551): 
W/jxcore-log( 6551): JXcore engine is started
,I/chromium( 6551): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6551): Toggling radios to true
I/jxcore-log( 6551): 
,D/BluetoothAdapter( 6551): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,D/WifiService(  885): setWifiEnabled: true pid=6551, uid=10435
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6551): Radios toggled
I/jxcore-log( 6551): 
,I/jxcore-log( 6551): My device name is: motorola-XT1072
I/jxcore-log( 6551): 
,I/wpa_supplicant( 1405): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297):  STA Disconnected !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
,I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  297): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/wpa_supplicant( 1405): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering(  885): InitialState.processMessage what=4
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
I/wpa_supplicant( 1405): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1405): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 21
D/TCMD    (  478): Listening for incoming client connection request
,V/NativeCrypto( 1749): Read error: ssl=0xb741ae30: I/O error during system call, Connection timed out
V/NativeCrypto( 1749): SSL shutdown failed: ssl=0xb741ae30: I/O error during system call, Broken pipe
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  885): connected time updated 121353
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6616 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 25.053ms
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.780ms
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.149ms
,I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/wpa_supplicant( 1405): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/wpa_supplicant( 1405): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1405): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6616): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6641 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 54552(2MB) AllocSpace objects, 3(233KB) LOS objects, 33% free, 20MB/30MB, paused 1.886ms total 183.858ms
,I/ActivityManager(  885): Killing 6320:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6320/cgroup.procs: No such file or directory
,W/ResourcesManager( 6641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  478): NL - Read 56 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  297): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1405): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  885): [1,452,520,979,923 ms] noteScanEnd no scan source
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  297): Event received = Trying to associate with
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1405): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@14b287eb sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6641): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6641): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6641): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6641): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6641): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6641): MmsConfig.loadFromResources
,E/Babel_SMS( 6641): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6641): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
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
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1405): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/MDMCTBK (  297): Event received = Associated with c0:ff:d4
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  478): NL - Read 80 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/Tethering(  885): ApnList is empty for checkDunConfigured()
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1405): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1405): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
,D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  297): Event received = WPA: Key negotiation com
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297):  STA Connected !!
E/MDMCTBK (  297): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  297): get_freq !!, resp=2412
I/MDMCTBK (  297): get_freq !!, Strip data
I/MDMCTBK (  297): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  297): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  297): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1207038008
I/MDMCTBK (  297): return from set_get_from_wpa_supplicant
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
D/MDMCTBK (  297): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  297): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  297): , reply_len: 3, ret: 0
E/MDMCTBK (  297): MdmCutbackHndler, resp=OK
E/MDMCTBK (  297): 
D/MDMCTBK (  297): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  295): Setting iface cfg
E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1405): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1405): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@130b8747 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@130b8747 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 6641): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6641): startup - clean
,I/Babel   ( 6641): deleted: false for 0
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6641): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6641): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6641): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6685): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6685): version 5.5.6 starting
W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
E/DHCPCD  ( 6685): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6685): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6685): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6357:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6685): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6685): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6685): wlan0: sending REQUEST (xid 0x77898d87), next in 4.12 seconds
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6357/cgroup.procs: No such file or directory
,I/vclib   ( 6641): onServiceConnected
W/Babel   ( 6641): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6685): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6685): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6685): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6685): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6685): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6685): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 20
,D/TCMD    (  478): Listening for incoming client connection request
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/DHCPCD  ( 6685): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
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
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:03:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452520982164], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452520982147]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1540): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1540): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=100
,V/AlarmManager(  885): send {3b632aff, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {189bbad2, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  885): done {189bbad2, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4ms]
,V/AlarmManager(  885): done {3b632aff, *alarm*:android.intent.action.TIME_TICK} [30ms]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  885): MasterInitialState.processMessage what=3
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2624): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6749 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1481): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2624): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2624): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2624): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2624): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2624): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2624): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2624): [debug] > CusSM.onRadioDown
,I/MusicStore( 6749): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6749): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/global frequency( 2624): no tags to log
,D/Checkin ( 2624): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6749): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6749): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6749): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6749): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2624): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/JNIHelp ( 6749): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,W/ActivityThread( 6749): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6749): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34e7d473: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6749): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6749): GMSCore installation verified
,I/ConfigStore( 6749): Config Database version: 1
,I/art     ( 1481): Explicit concurrent mark sweep GC freed 56347(3MB) AllocSpace objects, 37(1263KB) LOS objects, 40% free, 7MB/12MB, paused 1.102ms total 55.770ms
,D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2624): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/AlarmManager(  885): send {76d87f8, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/art     (  885): Explicit concurrent mark sweep GC freed 30987(1543KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.661ms total 122.340ms
,I/MediaRouter( 6749): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/BSUtils ( 2624): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,V/MusicLeanback( 6749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6749): type=WIFI subType= reason=null isConnected=true
,I/BSUtils ( 2624): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2624): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2624): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2624): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2624): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2624): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2624): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2624): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/NetworkMonitor( 6749): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6790 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6749): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6749): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6180:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6180/cgroup.procs: No such file or directory
,V/Mms     ( 6790): mnc/mcc: 
V/Mms     ( 6790): tag: int value: recipientLimit - 20
V/Mms     ( 6790): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6790): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6790): tag: int value: maxSubjectLength - 80
V/Mms     ( 6790): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6790): tag: bool value: enableGroupMms - false
V/Mms     ( 6790):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6790): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6820 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6259:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6820): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6259/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6820): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6820): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  885): Killing 6641:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6641/cgroup.procs: No such file or directory
,I/CheckinService( 6412): Checkin interval check for package: unspecified last checkin: 1452520903053 min interval config: 0 actual interval: 81169
,I/CheckinService( 6412): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6412): SYNC; picasa accounts
,D/NetworkLogImpl( 6412): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6412): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6412): num queued entries: 0
I/iu.UploadsManager( 6412): num updated entries: 0
I/iu.SyncManager( 6412): NEXT; no task
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6857 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6412): Checking schedule, now: 1452520984381 next: 1452520933022
I/CheckinService( 6412): active receiver: enabled
,I/CheckinService( 6412): Preparing to send checkin request
I/EventLogService( 6412): Accumulating logs since 1452520898885
,I/CheckinRequestBuilder( 6412): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
,E/ActivityThread( 6412): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6881 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6881): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6899 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6899): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6899): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6899): VM with version 2.1.0 has multidex support
I/MultiDex( 6899): install
I/MultiDex( 6899): VM has multidex support, MultiDex support library is disabled.
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): now: 197572 ,futureTime: 9223372036854775807
D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): now: 197572 ,futureTime: 9223372036854775807
D/PollingManager( 2624): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2624): now: 197573 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1481): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2624): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1481): now: 197581 ,futureTime: 86475199
D/Central_PollingManager( 1481): Polling alarm set to expire at: 86475199 Current Time: 197582
,D/OtaApp  ( 2624): [debug] > PollingManagerService, now: 197584 ,futureTime: 7976079
,D/OtaApp  ( 2624): [debug] > Polling alarm set to expire at: 7976079 Current Time: 197585
,I/NetworkMonitor( 6749): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2624): isDeviceProvisioned: deviceId = 2072049230914535424
,V/JNIHelp ( 6899): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 6881): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6881): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6881): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6881): MmsConfig.loadFromDatabase
,W/ActivityThread( 6899): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6899): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d431ab8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6899): Installed default security provider GmsCore_OpenSSL
,E/Babel_SMS( 6881): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6881): MmsConfig.loadFromResources
E/Babel_SMS( 6881): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6881): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 2624): Explicit concurrent mark sweep GC freed 25881(1580KB) AllocSpace objects, 4(87KB) LOS objects, 40% free, 11MB/19MB, paused 1.218ms total 102.727ms
,D/CCE     ( 2624): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2624): createDeviceIdOrLogin update_device
,D/Checkin ( 2624): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2624): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2624): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2624): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2624): createDeviceIdOrLogin update_device
,D/Checkin ( 2624): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 6899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (  885): Explicit concurrent mark sweep GC freed 10663(499KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.859ms total 124.781ms
,D/MMApiProvisionService( 2624): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2624): set mOutstandingReq to true.
I/ Nonce  ( 2624):  Nonce getNonce 
I/ Nonce  ( 2624):  Nonce Request 
I/ Nonce  ( 2624):  Nonce execute Request 
,D/MMApiWebService( 2624): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/NativeLibraryUtils( 6899): Install completed successfully. count=14 extracted=0
I/art     ( 1481): Explicit concurrent mark sweep GC freed 4247(184KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 855us total 28.936ms
,W/Settings( 6881): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6881): startup - clean
,D/MMApiProvisionService( 2624): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2624): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2624): createDeviceIdOrLogin update_device
,D/Checkin ( 2624): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2624): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2624): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2624): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/Babel   ( 6881): deleted: false for 0
,D/OtaApp  ( 2624): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2624): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2624): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2624): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2624): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2624): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2624): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2624): generating token using payload instead of using session token
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6938 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ Nonce  ( 2624):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2624): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2624): publish the event [tag = MOT_CCE event name = LOG]
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,W/VideoCapabilities( 6881): Unrecognized profile 2130706433 for video/avc
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
W/AudioCapabilities( 6881): Unsupported mime audio/amr-wb-plus
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xbea354e0
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb7ed8280, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f4b430, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fa5790, idLength=0xb55d7730
,W/VideoCapabilities( 6881): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=4045689978
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e5f810
D/DrmWidevineDash(  300): message_length=1591, signature=0xb7e5fe50, signature_length=3042801428
,I/VideoCapabilities( 6881): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6881): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6881): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6881): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6881): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6881): onServiceConnected
W/Babel   ( 6881): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 6881): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  885): Killing 6616:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6616/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/dex2oat ( 6965): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/GAv4    ( 6938): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6938):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6938):   adb logcat -s GAv4
,W/GAv4    ( 6938): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6938): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6938): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6965): dex2oat took 116.666ms (threads: 4)
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6899): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6899): Local Branch: 
I/Adreno-EGL( 6899): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6899): Local Patches: NONE
I/Adreno-EGL( 6899): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6899): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6899): Local Branch: 
I/Adreno-EGL( 6899): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6899): Local Patches: NONE
I/Adreno-EGL( 6899): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6938): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6938): Time to load native libraries: 2 ms (timestamps 9133-9135)
I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6938): Binding Chromium to main looper Looper (main, tid 1) {a0ea1e8}
I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
I/chromium( 6938): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6938): Initializing chromium process, singleProcess=true
,W/art     ( 6938): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6938): ApplicationContext is null in ApplicationStatus
,W/chromium( 6938): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6938): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6938): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6938): Local Branch: 
I/Adreno-EGL( 6938): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6938): Local Patches: NONE
I/Adreno-EGL( 6938): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
I/NSApplication( 6938): Starting up...
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,I/ Nonce  ( 2624):  Nonce Reponse 
D/        ( 2624): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"c54670ea-5905-4518-894e-e43ba2b80f5b"}
D/MMApiWSBase( 2624): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2624):  Nonce Handle Reponse 
D/MMApiProvisionService( 2624): mOutstandingReq set to false
W/AudioManagerAndroid( 6938): Requires BLUETOOTH permission
D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb55d7960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb7f4c9b8, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7010 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6749:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f4b430, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fa57d0, idLength=0xb1412730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=2246556839
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f59ed8
D/DrmWidevineDash(  300): message_length=1626, signature=0xb7e5fe70, signature_length=2973837076
D/MMApiProvisionService( 2624):  pTime 1452467391223 sExp 172742 cTime 1452520986877 tTime 1452640133223
D/MMApiProvisionService( 2624):  No login Required 
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6749/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6899): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6899): Local Branch: 
I/Adreno-EGL( 6899): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6899): Local Patches: NONE
I/Adreno-EGL( 6899): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7032 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6790:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6899): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6899): Local Branch: 
I/Adreno-EGL( 6899): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6899): Local Patches: NONE
I/Adreno-EGL( 6899): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/DataUsage( 2624): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2624): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6790/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6412): Classify the device as Phone.
,W/ResourcesManager( 7032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6412): Sending checkin request (9515 bytes)
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7056 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.232ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 18.950ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.219ms
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7079 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6857:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7056): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 6820:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6857/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6820/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6412): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6412): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 7079): Database version: 120
,I/art     ( 6385): Explicit concurrent mark sweep GC freed 1599(69KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 429us total 29.010ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6412): Classify the device as Phone.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6412): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6412): Checking schedule, now: 1452520988478 next: 1453122125465
I/CheckinService( 6412): active receiver: disabled
,D/CheckinService( 6412): Recording last checkin time for package unspecified as 1452520988490
,I/ActivityManager(  885): Killing 6881:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 7079): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6881/cgroup.procs: No such file or directory
,V/JNIHelp ( 7079): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7079): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7079): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34e7d473: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7079): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7079): GMSCore installation verified
,I/ConfigStore( 7079): Config Database version: 1
,I/art     (  885): Explicit concurrent mark sweep GC freed 9974(518KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.673ms total 111.432ms
,I/MediaRouter( 7079): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7079): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7079): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Killing 6938:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_6938/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7139 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NetworkMonitor( 7079): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 7079): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7079): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7010:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7139): mnc/mcc: 
,V/Mms     ( 7139): tag: int value: recipientLimit - 20
,V/Mms     ( 7139): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7139): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7139): tag: int value: maxSubjectLength - 80
V/Mms     ( 7139): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7139): tag: bool value: enableGroupMms - false
V/Mms     ( 7139):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7010/cgroup.procs: No such file or directory
,W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310938, SEQNUM=4455, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-21634, POWER_SUPPLY_CHARGE_COUNTER=-427, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7175 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7032:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 7175): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7032/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2488): Disconnected process message: 10, size: 0
,D/MobileConnectivityChangeReceiver( 7175): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7175): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7056:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7056/cgroup.procs: No such file or directory
,I/CheckinService( 6412): Checkin interval check for package: unspecified last checkin: 1452520988490 min interval config: 0 actual interval: 1890
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7200 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6412): Checking schedule, now: 1452520990485 next: 1452521018465
I/CheckinService( 6412): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7223 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7079:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7079/cgroup.procs: No such file or directory
,W/ResourcesManager( 7223): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7223): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7223): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7223): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7223): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7223): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7223): MmsConfig.loadFromResources
,E/Babel_SMS( 7223): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7223): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7223): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7223): startup - clean
,I/Babel   ( 7223): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7263 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7223): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7223): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7223): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7223): onServiceConnected
W/Babel   ( 7223): Attempted to change video mute state without an active call.
,I/GAv4    ( 7263): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7263):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7263):   adb logcat -s GAv4
I/Babel   ( 7223): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7139:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 6551): Test app app.js loaded
I/jxcore-log( 6551): 
,I/chromium( 6551): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7139/cgroup.procs: No such file or directory
,W/GAv4    ( 7263): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7263): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7263): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7263): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7263): Time to load native libraries: 2 ms (timestamps 4660-4662)
I/LibraryLoader( 7263): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7263): Binding Chromium to main looper Looper (main, tid 1) {a0ea1e8}
,I/LibraryLoader( 7263): Expected native library version number "",actual native library version number ""
I/chromium( 7263): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7263): Initializing chromium process, singleProcess=true
,W/art     ( 7263): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7263): ApplicationContext is null in ApplicationStatus
,W/chromium( 7263): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7263): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7263): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7263): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7263): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7263): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7263): Local Branch: 
I/Adreno-EGL( 7263): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7263): Local Patches: NONE
I/Adreno-EGL( 7263): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7263): Starting up...
,W/AudioManagerAndroid( 7263): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7329 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7175:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7175/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7348 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7200:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7200/cgroup.procs: No such file or directory
,W/ResourcesManager( 7348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7368 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7263:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7368): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7263/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 6899:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2624): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6899/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2624): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2624): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2624): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2624): onServiceConnected()
,D/GetNotificationsWS( 2624): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2624): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2624): started with background data enabled, making sure notification mechanism is enabled
,V/AlarmManager(  885): done {76d87f8, *walarm*:com.google.android.intent.action.SEND_IDLE} [10134ms]
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7398 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7420 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.589ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.355ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.088ms
,I/ActivityManager(  885): Killing 6412:com.google.android.gms/u0a16 (adj 15): empty #7
,I/MusicStore( 7420): Database version: 120
,D/WifiService(  885): Client connection lost with reason: 4
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6412/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7420): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:32000 mC
,W/ActivityThread( 7420): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7420): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34e7d473: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7420): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7420): GMSCore installation verified
,I/ConfigStore( 7420): Config Database version: 1
,I/art     (  885): Explicit concurrent mark sweep GC freed 12161(614KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.667ms total 125.667ms
,I/MediaRouter( 7420): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7420): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7420): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7420): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7459 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7420): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7420): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7477 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,V/Mms     ( 7459): mnc/mcc: 
,V/Mms     ( 7459): tag: int value: recipientLimit - 20
V/Mms     ( 7459): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7459): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7459): tag: int value: maxSubjectLength - 80
V/Mms     ( 7459): tag: bool value: smsForceShowEncodingMenu - true
I/ActivityManager(  885): Killing 7329:com.android.chrome/u0a52 (adj 15): empty #7
V/Mms     ( 7459): tag: bool value: enableGroupMms - false
V/Mms     ( 7459):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7477): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7477): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/MultiDex( 7477): VM with version 2.1.0 has multidex support
I/MultiDex( 7477): install
I/MultiDex( 7477): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7329/cgroup.procs: No such file or directory
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@38eec8bf
,I/GCoreNlp( 1749): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7515 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/JNIHelp ( 7477): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 7515): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7515): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7515): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7348:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ActivityThread( 7477): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7477): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f824c7e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7477): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7348/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7368:android.process.acore/u0a7 (adj 15): empty #7
,D/NativeLibraryUtils( 7477): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7368/cgroup.procs: No such file or directory
,I/CheckinService( 7477): Checkin interval check for package: unspecified last checkin: 1452520988490 min interval config: 0 actual interval: 6485
,I/CheckinService( 7477): Disabling old GoogleServicesFramework version
,I/CheckinService( 7477): Checkin interval check for package: unspecified last checkin: 1452520988490 min interval config: 0 actual interval: 6499
,I/CheckinService( 7477): Checking schedule, now: 1452520994999 next: 1452521018465
,I/CheckinService( 7477): active receiver: disabled
,I/CheckinService( 7477): Checking schedule, now: 1452520995028 next: 1452521018465
I/CheckinService( 7477): active receiver: disabled
,I/iu.SyncManager( 7477): SYNC; picasa accounts
,D/NetworkLogImpl( 7477): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7477): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 7477): num queued entries: 0
,I/iu.UploadsManager( 7477): num updated entries: 0
I/iu.SyncManager( 7477): NEXT; no task
,I/ActivityManager(  885): Killing 7223:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7223/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7554 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7554): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7554): MmsConfig.loadMmsSettings
I/Babel_SMS( 7554): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7554): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7554): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7554): MmsConfig.loadFromResources
,E/Babel_SMS( 7554): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7554): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7554): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7554): startup - clean
,I/Babel   ( 7554): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7588 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7554): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7554): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7554): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7554): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7554): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7554): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7554): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7554): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7554): onServiceConnected
,W/Babel   ( 7554): Attempted to change video mute state without an active call.
,I/GAv4    ( 7588): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7588):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7588):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7588): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7588): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7588): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7554): connection state changed from UNKNOWN to CONNECTED
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7588): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  885): Killing 7420:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7588): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7588): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7588): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7420/cgroup.procs: No such file or directory
,I/WebViewFactory( 7588): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7588): Time to load native libraries: 1 ms (timestamps 8636-8637)
I/LibraryLoader( 7588): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7588): Binding Chromium to main looper Looper (main, tid 1) {a0ea1e8}
,I/LibraryLoader( 7588): Expected native library version number "",actual native library version number ""
I/chromium( 7588): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7588): Initializing chromium process, singleProcess=true
,W/art     ( 7588): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7588): ApplicationContext is null in ApplicationStatus
,W/chromium( 7588): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7588): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7588): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7588): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7588): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7588): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7588): Local Branch: 
I/Adreno-EGL( 7588): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7588): Local Patches: NONE
I/Adreno-EGL( 7588): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7588): Requires BLUETOOTH permission
,I/NSApplication( 7588): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7659 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7459:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7459/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 17594(884KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 120.884ms
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7678 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7515:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7515/cgroup.procs: No such file or directory
,W/ResourcesManager( 7678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7698 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7554:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7698): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7398:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7554/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2624): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7398/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2624): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2624): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2624): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2624): onServiceConnected()
D/GetNotificationsWS( 2624): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2624): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2624): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1749): callingUid 10016, callindPid: 1749
,D/LocationInitializer( 7477): Restart initialization of location
,W/IcingInternalCorpora( 7477): getNumBytesRead when not calculated.
,I/art     ( 1749): Explicit concurrent mark sweep GC freed 106665(5MB) AllocSpace objects, 30(503KB) LOS objects, 40% free, 15MB/25MB, paused 1.199ms total 148.922ms
,E/MDM     ( 1749): [199] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2624): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
I/art     ( 7477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/OtaApp  ( 2624): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2624): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2624): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2624): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2624): publish the event [tag = MOT_OTA event name = LOG]
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1099a540)
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31450c79)
E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22c95dbe)
E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2940fe1f)
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@913d56c)
,D/OtaApp  ( 2624): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2624): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2624): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7741 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2624): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2624): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2624): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2624): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2624): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2624): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1421): onFinishInput()
,W/IInputConnectionWrapper( 6551): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7741): Register our PhoneStateListener
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,168
,V/SetupWizard( 7741): Connected to Gservices successfully
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7763 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7788 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7588:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  318): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 27.869ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.266ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.217ms
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7588/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7812 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7829 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7659:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7678:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7659/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7678/cgroup.procs: No such file or directory
,W/ResourcesManager( 7829): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7829): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7829): MmsConfig.loadMmsSettings
I/Babel_SMS( 7829): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7829): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7829): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7829): MmsConfig.loadFromResources
,E/Babel_SMS( 7829): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7829): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7829): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7829): startup - clean
,I/Babel   ( 7829): deleted: false for 0
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7863 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7829): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7829): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7829): Unsupported mime video/mpeg2
,W/asset   ( 7863): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7863): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7863): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7863): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7829): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7829): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7829): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7829): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7829): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 7477): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@110e3079 new=com.google.android.velvet.VelvetApplication@110e3079
,I/UpdateIcingCorporaServi( 7788): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 7477): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7889 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 7477): Storage manager: low false usage 1.73MB avail 3.12GB capacity 4.85GB
,I/vclib   ( 7829): onServiceConnected
,W/Babel   ( 7829): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7788): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
,I/ActivityManager(  885): Killing 7741:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7741/cgroup.procs: No such file or directory
,W/System  ( 7829): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7829): Installed default security provider GmsCore_OpenSSL
,I/art     (  885): Explicit concurrent mark sweep GC freed 11646(576KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.874ms total 123.172ms
,I/Icing   ( 7477): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7933 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7763:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7763/cgroup.procs: No such file or directory
,I/Icing   ( 7477): Internal init done: storage state 0
,I/Icing   ( 7477): Post-init done
,I/Icing   ( 7477): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7933): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7933): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7933): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7933): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7933): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7933): Skipping gmscore version check
D/Finsky  ( 7933): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7933): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/MDM     ( 1749): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7477): Restart initialization of location
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/Finsky  ( 7933): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Killing 7812:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_7812/cgroup.procs: No such file or directory
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,W/FusedLocationProvider( 1749): location=null
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7985 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7985): Register our PhoneStateListener
,I/ActivityManager(  885): Killing 7863:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_7863/cgroup.procs: No such file or directory
,I/CheckinService( 7477): Checkin interval check for package: unspecified last checkin: 1452520988490 min interval config: 0 actual interval: 11782
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8004 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 7477): Checking schedule, now: 1452521000312 next: 1452521018465
,I/CheckinService( 7477): active receiver: disabled
,D/TaskPersister(  885): removeObsoleteFile: deleting file=2_task.xml
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Killing 7788:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_7788/cgroup.procs: No such file or directory
,I/Icing   ( 7477): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 7477): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7477): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  885): Killing 7829:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7829/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7698:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7698/cgroup.procs: No such file or directory
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,W/SQLiteConnectionPool( 7477): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:31000 mC
,I/CheckinService( 7477): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310563, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8513, POWER_SUPPLY_CHARGE_COUNTER=-568, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2488): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2488): Disconnected process message: 10, size: 0
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {3b551b59, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  885): send {3d430a70, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {3b551b59, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [17ms]
V/AlarmManager(  885): done {3d430a70, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,I/CheckinService( 7477): Checkin interval check for package: unspecified last checkin: 1452520988490 min interval config: 0 actual interval: 46459
,I/CheckinService( 7477): Checking schedule, now: 1452521034961 next: 1452521018465
I/CheckinService( 7477): active receiver: enabled
,I/CheckinService( 7477): Preparing to send checkin request
,I/EventLogService( 7477): Accumulating logs since 1452520984485
,I/CheckinRequestBuilder( 7477): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
E/ActivityThread( 7477): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8060 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8060): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8060): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8060): VM with version 2.1.0 has multidex support
,I/MultiDex( 8060): install
I/MultiDex( 8060): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8060): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8060): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8060): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d431ab8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8060): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1749): callingUid 10016, callindPid: 1749
,E/MDM     ( 1749): [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 7477): Restart initialization of location
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
,I/art     ( 8060): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8060): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8060): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
,I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
,I/art     ( 8060): Background sticky concurrent mark sweep GC freed 23880(1419KB) AllocSpace objects, 2(32KB) LOS objects, 4% free, 10MB/11MB, paused 7.212ms total 76.975ms
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb1412960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb7ed7fe8, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7ebc998, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fa57b0, idLength=0xb55d7730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=1680682906
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e5ba00
D/DrmWidevineDash(  300): message_length=1591, signature=0xb7ed8180, signature_length=3042801428
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8102): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8102): dex2oat took 69.589ms (threads: 4)
,I/Adreno-EGL( 8060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8060): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8060): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8060): Local Branch: 
I/Adreno-EGL( 8060): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8060): Local Patches: NONE
I/Adreno-EGL( 8060): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8060): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8060): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8060): Local Branch: 
I/Adreno-EGL( 8060): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8060): Local Patches: NONE
I/Adreno-EGL( 8060): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
,E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffc000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  300): hlos api version =  9
,D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb1412960
,D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb7edf018, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f4b430, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fa57d0, idLength=0xb54d7730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
,D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=833714422
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7ed44b8
D/DrmWidevineDash(  300): message_length=1626, signature=0xb7e5f810, signature_length=3041752852
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8060): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8060): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8060): Local Branch: 
I/Adreno-EGL( 8060): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8060): Local Patches: NONE
I/Adreno-EGL( 8060): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8060): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8060): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8060): Local Branch: 
I/Adreno-EGL( 8060): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8060): Local Patches: NONE
I/Adreno-EGL( 8060): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 7477): Classify the device as Phone.
,I/CheckinTask( 7477): Sending checkin request (9512 bytes)
,I/CheckinRequestBuilder( 7477): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 7477): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 7477): Classify the device as Phone.
,I/art     (  885): Explicit concurrent mark sweep GC freed 13752(671KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.880ms total 113.595ms
,I/CheckinTask( 7477): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7477): Checking schedule, now: 1452521039249 next: 1453122176239
I/CheckinService( 7477): active receiver: disabled
,D/CheckinService( 7477): Recording last checkin time for package unspecified as 1452521039264
,V/SetupWizard( 7985): Connected to Gservices successfully
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Killing 7889:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7889/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1749): disconnect managed GoogleApiClient
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8149 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37f6e2bc
,I/GCoreNlp( 1749): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8178 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8196 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7933:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.665ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.919ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 23.122ms
,I/ActivityManager(  885): Killing 8004:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_7933/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8004/cgroup.procs: No such file or directory
,W/ResourcesManager( 8196): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8196): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8196): MmsConfig.loadMmsSettings
I/Babel_SMS( 8196): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8196): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8196): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8196): MmsConfig.loadFromResources
,E/Babel_SMS( 8196): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8196): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8196): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8196): startup - clean
,I/Babel   ( 8196): deleted: false for 0
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8228 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8196): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8196): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8196): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8196): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8196): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8196): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8196): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8196): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8249 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7985:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8228): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7985/cgroup.procs: No such file or directory
,I/vclib   ( 8196): onServiceConnected
W/Babel   ( 8196): Attempted to change video mute state without an active call.
,W/asset   ( 8249): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8249): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8249): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8249): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/ResourcesManager( 8196): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8196): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 7477): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7477): Null package name or gms related package.  Ignoreing.
,V/JNIHelp ( 8196): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@110e3079 new=com.google.android.velvet.VelvetApplication@110e3079
,I/UpdateIcingCorporaServi( 8149): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 7477): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8283 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8196): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8196): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8149): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8310 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8060:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_8060/cgroup.procs: No such file or directory
,D/Finsky  ( 8310): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8310): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8310): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8310): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8310): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8310): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8310): Skipping gmscore version check
,I/ActivityManager(  885): Killing 8178:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8178/cgroup.procs: No such file or directory
,D/Finsky  ( 8310): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8310): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 7477): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 7477): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 8249:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8249/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 8196:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8196/cgroup.procs: No such file or directory
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
,I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1749): onCreate
,I/ConfigService( 1749): onDestroy
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311035, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-764, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2488): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2488): Disconnected process message: 10, size: 0
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6551): --= Surplus to requirements =--
I/jxcore-log( 6551): 
I/jxcore-log( 6551): ****TEST TOOK:  ms ****
I/jxcore-log( 6551): 
I/jxcore-log( 6551): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6551): 
,D/AndroidRuntime( 8384): 
D/AndroidRuntime( 8384): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8384): CheckJNI is OFF
,D/AndroidRuntime( 8384): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10435 user=-1: uninstall pkg
,I/ActivityManager(  885): Killing 6551:com.test.thalitest/u0a435 (adj 9): stop com.test.thalitest
,W/PackageSettings(  885): Skipping PackageSetting{11ed468c com.example.hello/10426} due to missing metadata
,I/WindowState(  885): WIN DEATH: Window{171d0e95 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  885): Client connection lost with reason: 4
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{3b5d3716 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  885): Spurious death for ProcessRecord{7b6a6bd 6551:com.test.thalitest/u0a435}, curProc for 6551: null
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10435 user=0: pkg removed
I/ActivityManager(  885):   Force finishing activity ActivityRecord{3b5d3716 u0 com.test.thalitest/.MainActivity t3 f}
,W/ActivityManager(  885): Duplicate finish request for ActivityRecord{3b5d3716 u0 com.test.thalitest/.MainActivity t3 f}
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1421): resetDictionaries() : en_US
,I/art     ( 3009): Explicit concurrent mark sweep GC freed 10280(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 7MB/12MB, paused 1.061ms total 57.286ms
I/Keyboard.Facilitator.DecoderInitializer( 1421): run()
,I/Decoder ( 1421): createOrResetDecoder
,D/VoicemailCleanupService( 8228): Cleaning up data for package: com.test.thalitest
,I/art     ( 1576): Explicit concurrent mark sweep GC freed 5071(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 487us total 93.088ms
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8416 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 24752(1532KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.696ms total 148.058ms
,I/art     (  885): WaitForGcToComplete blocked for 112.682ms for cause Explicit
,I/ConfigService( 1749): onCreate
,W/asset   ( 8416): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8416): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8416): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8416): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1421): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1421): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1421): run()
,I/StatsUtilsManager( 1421): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1421): shouldRecordStats() = Too Soon
,I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8442 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  885): removeObsoleteFile: deleting file=3_task.xml
,I/ActivityManager(  885): Killing 8149:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Launcher( 1576): Deferring update until onResume
,I/art     (  885): Explicit concurrent mark sweep GC freed 7006(376KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.737ms total 218.666ms
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8149/cgroup.procs: No such file or directory
,W/ContextImpl( 8442): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 7477): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 7477): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 7477): Reading stored module config
,D/ChimeraCfgMgr( 7477): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 7477): Loading module APK com.google.android.play.games
,D/AndroidRuntime( 8384): Shutting down VM
,I/LocationSettingsChecker( 7477): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 7477): App measurement is starting up, version: 8489
,I/GMPM-SVC( 7477): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1749): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1749): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 7477): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 7477): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 7477): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 7477): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 7477): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 7477): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 7477): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 7477): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 7477): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 7477): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 7477): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 7477): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 7477): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8472 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 7477): doRemovePackageData com.test.thalitest
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@110e3079 new=com.google.android.velvet.VelvetApplication@110e3079
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8494 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 7477): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7477): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 7477): CM callback handler got msg 524290
,E/BaseAppContext( 7477): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8533 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 8472): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BaseAppContext( 7477): Using Auth Proxy for data requests.
,E/SQLiteDatabase( 7477): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 7477): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 7477): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 7477): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 7477): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7477): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7477): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7477): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7477): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 7477): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 7477): Process: com.google.android.gms, PID: 7477
E/AndroidRuntime( 7477): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 7477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 7477): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 7477): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 7477): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 7477): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 7477): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7477): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7477): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7477): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 7477): Sending signal. PID: 7477 SIG: 9
,E/lowmemorykiller(  277): Error writing /proc/7477/oom_score_adj; errno=22
,D/WifiService(  885): Client connection lost with reason: 4
,D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3d47c793)
,D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 8472): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
,E/SQLiteLog( 8472): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
